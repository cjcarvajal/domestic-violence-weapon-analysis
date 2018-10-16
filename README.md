# Domestic Violence in Colombia - Temporal Analysis on weapons (Aggresions with scopolamine?)

![alt text](https://github.com/cjcarvajal/domestic-violence-weapon-analysis/blob/master/img.png)

Keeping on the analysis about domestic violence that begin [here](https://github.com/cjcarvajal/domestic-violence-viz), I turned my attention to the weapons used in the incidents. The aggressions were perpetrated with guns, knifes, drugs or no weapons at all. One kind of drug caught my attention and made me look the data in detail, that was **scopolamine**. Scopolamine is a drug used to rob, rape or kidnap people so it's a shock to see this drug been used in domestic violence. Having temporal data was a great opportunity to look for trends in the use of weapons and outliers. The visualization presented here intends to help with this tasks and answer some question about the use of drugs in the incidents.

## Dataset

The data was taken from an official goverment page [Datos Abiertos](https://www.datos.gov.co/Seguridad-y-Defensa/Violencia-intrafamiliar-2018/s9rg-bzb5)

## The Technology Used

In order to run this project, you just need to download the index.html file an open it in your browser, although not necessary, you could install a local http server on your machine, and serve the index html file from there, the easiest way (I think) is using the [SimpleHTTPServer](https://docs.python.org/2/library/simplehttpserver.html) Python utility, just be sure to have Python installed in your machine, go to the folder where you download the index.html and run:

```
python -m SimpleHTTPServer 8080
```

Open your browser and type http://localhost:8080/ and voila!

Although is not necessary to run the project, you may want to learn this technologies which were used to build the visualization.

* [Javascript](https://www.w3schools.com/js/)
* [D3 version 5](https://d3js.org/)
* [css](https://www.w3schools.com/Css/)
* [html](https://www.w3schools.com/html/)

I have used most of the Mike Bostock code for making a calendar view, check the original version [here]. (https://beta.observablehq.com/@mbostock/d3-calendar-view)

## Live Project

I have published my project in githubpages, so you can check it right [here](https://cjcarvajal.github.io/weapon-analysis).

### License

This project has MIT license which can be consulted in the LICENSE of this repository.