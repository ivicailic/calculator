//ja
function sleep(){
	i++;
	if(i>5){
	i = 0;
	ar = ponovoNapuni();
	}
	omot.innerHTML = "";
	start();	
}
function ponovoNapuni(){
var text = 'radno vreme:';
var text1 = 'od 8:00 do 20:00 casova';
var text2 = 'najpovoljniji otkupni kurs';
var text3 = 'moguc svaki dogovor';
var text4 = 'uskoro platni promet';
var text5 = 'hvala na saradnji';


var stext = text.split('');
var stext1 = text1.split('');
var stext2 = text2.split('');
var stext3 = text3.split('');
var stext4 = text4.split('');
var stext5 = text5.split('');
var nasArray = [stext,stext1,stext2,stext3,stext4,stext5];
return nasArray;
}
var ar = ponovoNapuni();
var omot = document.getElementById('omot');
var x ;

var i = 0;

function start(){
	if(ar[i].length>0){
	omot.innerHTML += ar[i].shift();	
	var x = setTimeout(start,200);
	}else{
	var ss = setTimeout(sleep,2000);
	}
	}
	start();
	var vreme = document.getElementById('vreme');
var s;

function prikaziVreme () {
	
	var sada = new Date();
	var i = sada.getDay();
	var g = sada.getFullYear();
	var mes = sada.getMonth();
	var d = sada.getDate();
	var h = sada.getHours();
	var m = sada.getMinutes();
	var sp = sada.getSeconds();
	
	vreme.innerHTML =  h+':'+m+':'+sp
	vreme1.innerHTML =  d+'. '+(mes+1)+'. '+g
}
s = setInterval(prikaziVreme,1000);