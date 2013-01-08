AskEniz
=======

HTML5 Canvas Donut Chart  is connected with searchbox results. 

It uses HTML 5 Canvas, jQuery, jQuery UI AutoComplete. I was inspired by Ask KEN (http://askken.heroku.com)

AskEniz is basically a textual search box and the matching entires from Data.js are visualized as a donut chart.

I used a simple JSON Array Data:

Data =[ 
{
    Id: "Sakarya",
    Name: "Sakarya",
    Info:"Sakarya Şehri",
    Detail: 
        [
            { Id: "Ogun", Name: "Ogün Altıparmak", Info: "Futbolcu" },
            {Id:"Sapanca",Name:"Sapanca Gölü",Info:"Göl"}
        ]
},
{
    Id: "Ogun",
    Name: "Ogün Altıparmak",
    Info:"Futbolcu",
    Detail: 
        [
            { Id: "Trabzon", Name: "Trabzon", Info: "Şehir" },
            { Id: "Sakarya", Name: "Sakarya", Info: "Sakarya Şehri" },
            {Id:"Trabzon Spor",Name:"Trabzon Spor",Info:"Futbol Klübü"}
        ]
},
{
    Id: "Sapanca",
    Name: "Sapanca Gölü",
    Info:"Göl",
    Detail: 
        [
            { Id: "Sakarya", Name: "Sakarya", Info: "Sakarya Şehri" }
        ]
}
]
