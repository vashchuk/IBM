// Probably the best function in the world:
function GetPlace (place) {
    var actual;
    if (place=="Chile"){
        if (SpyChoice < 0.33){
            actual = "Peru";}
        else if (SpyChoice < 0.66){
            actual = "Bolivia";}
        else if (SpyChoice < 1){
            actual = "Argentina";}
        else {
            actual = "Proval";};
    }
    if (place=="Argentina"){
        if (SpyChoice < 0.2){
            actual = "Brasil";}
        else if (SpyChoice < 0.4){
            actual = "Uruguay";}
        else if (SpyChoice < 0.6){
            actual = "Paraguay";}
        else if (SpyChoice < 0.8){
            actual = "Bolivia";}
        else if (SpyChoice < 1) {
            actual = "Chile";}
        else {
            actual = "Proval";};
    }
    if (place=="Uruguay"){
        if (SpyChoice < 0.5){
            actual = "Brasil";}
        else if (SpyChoice < 1){
            actual = "Argentina";}
        else {
            actual = "Proval";};
    }
    if (place=="Paraguay"){
        if (SpyChoice < 0.33){
            actual = "Brasil";}
        else if (SpyChoice < 0.66){
            actual = "Bolivia";}
        else if (SpyChoice < 1){
            actual = "Argentina";}
        else {
            actual = "Proval";};
    }
    if (place=="Bolivia"){
        if (SpyChoice < 0.2){
            actual = "Brasil";}
        else if (SpyChoice < 0.4){
            actual = "Peru";}
        else if (SpyChoice < 0.6){
            actual = "Paraguay";}
        else if (SpyChoice < 0.8){
            actual = "Argentina";}
        else if (SpyChoice < 1) {
            actual = "Chile";}
        else {
            actual = "Proval";};
    }
    if (place=="Peru"){
        if (SpyChoice < 0.2){
            actual = "Brasil";}
        else if (SpyChoice < 0.4){
            actual = "Ecuador";}
        else if (SpyChoice < 0.6){
            actual = "Bolivia";}
        else if (SpyChoice < 0.8){
            actual = "Colombia";}
        else if (SpyChoice < 1) {
            actual = "Chile";}
        else {
            actual = "Proval";};
    }
    if (place=="Brasil"){
        if (SpyChoice < 0.1){
            actual = "Uruguay";}
        else if (SpyChoice < 0.2){
            actual = "Argentina";}
        else if (SpyChoice < 0.3){
            actual = "Paraguay";}
        else if (SpyChoice < 0.4){
            actual = "Bolivia";}
        else if (SpyChoice < 0.5) {
            actual = "Peru";}
        else if (SpyChoice < 0.6) {
            actual = "Colombia";}
        else if (SpyChoice < 0.7) {
            actual = "Venezuela";}
        else if (SpyChoice < 0.8) {
            actual = "Guyana";}  
        else if (SpyChoice < 0.9) {
            actual = "Suriname";} 
        else if (SpyChoice < 1) {
            actual = "French Guiana";}  
        else {
            actual = "Proval";};
    }
    if (place=="Ecuador"){
        if (SpyChoice < 0.5){
            actual = "Colombia";}
        else if (SpyChoice < 1){
            actual = "Peru";}
        else {
            actual = "Proval";};
    }
    if (place=="Colombia"){
        if (SpyChoice < 0.25){
            actual = "Brasil";}
        else if (SpyChoice < 0.5){
            actual = "Venezuela";}
        else if (SpyChoice < 0.75){
            actual = "Peru";}
        else if (SpyChoice < 1) {
            actual = "Ecuador";}
        else {
            actual = "Proval";};
    }
    if (place=="Venezuela"){
        if (SpyChoice < 0.33){
            actual = "Brasil";}
        else if (SpyChoice < 0.66){
            actual = "Guyana";}
        else if (SpyChoice < 1){
            actual = "Colombia";}
        else {
            actual = "Proval";};
    }
    if (place=="Guyana"){
        if (SpyChoice < 0.33){
            actual = "Brasil";}
        else if (SpyChoice < 0.66){
            actual = "Venezuela";}
        else if (SpyChoice < 1) {
            actual = "Suriname";}
        else {
            actual = "Proval";};
    }
    if (place=="Suriname"){
        if (SpyChoice < 0.33){
            actual = "Brasil";}
        else if (SpyChoice < 0.66){
            actual = "Guyana";}
        else if (SpyChoice < 1) {
            actual = "French Guiana";}
        else {
            actual = "Proval";};
    }
    if (place=="French Guiana"){
        if (SpyChoice < 0.5){
            actual = "Brasil";}
        else if (SpyChoice < 1) {
            actual = "Suriname";}
        else {
            actual = "Proval";};
    }
place=actual;
SpyChoice=Math.random();
return place;
};
  var SpyChoice=Math.random();
  var z=0;
  var Brasil=0;
  var Ecuador=0;
  var Peru=0;
  var Argentina=0;
  var Paraguay=0;
  var Uruguay=0;
  var Guyana=0;
  var FrenchGuiana=0;
  var Suriname=0;
  var Venezuela=0;
  var Chile=0;
  var Colombia=0;
  var Bolivia=0;
   while (z<1000){
    var a;
    a=GetPlace("Chile");
    var b;
    b=GetPlace(a);
    var c;
    c=GetPlace(b);
    var d;
    d=GetPlace(c);
    var e;
    e=GetPlace(d);
    var f;
    f=GetPlace(e);
    var g;
    g=GetPlace(f);
    var h;
    h=GetPlace(g);
    var i;
    i=GetPlace(h);
    var j;
    j=GetPlace(i);
    var k;
    k=GetPlace(j);
    var l;
    l=GetPlace(k);
    var m;
    m=GetPlace(l);
    var n;
    n=GetPlace(m);
    var o;
    o=GetPlace(n);
        if(o=="Brasil"){
          Brasil=Brasil+1;}
        else if(o=="Chile"){
          Chile=Chile+1;}
        else if(o=="Ecuador"){
          Ecuador=Ecuador+1;}
        else if(o=="Peru"){
            Peru=Peru+1;}
        else if(o=="Venezuela"){
            Venezuela=Venezuela+1;}
        else if(o=="Argentina"){
            Argentina=Argentina+1;}
        else if(o=="Uruguay"){
            Uruguay=Uruguay+1;}
        else if(o=="Paraguay"){
            Paraguay=Paraguay+1;}
        else if(o=="Bolivia"){
            Bolivia=Bolivia+1;}
        else if( o=="Colombia"){
            Colombia=Colombia+1;}
        else if (o=="Guyana"){
            Guyana=Guyana+1;}
        else if (o=="Suriname"){
            Suriname=Suriname+1;}
        else if (o=="French Guiana"){
            FrenchGuiana=FrenchGuiana+1;}
    z=z+1;
}
console.log("Brasil"+" "+Brasil/10+"%");
console.log("Chile"+" "+Chile/10+"%");
console.log("Ecuador"+" "+Ecuador/10+"%");
console.log("Peru"+" "+Peru/10+"%");
console.log("Venezuela"+" "+Venezuela/10+"%");
console.log("Argentina"+" "+Argentina/10+"%");
console.log("Uruguay"+" "+Uruguay/10+"%");
console.log("Paraguay"+" "+Paraguay/10+"%");
console.log("Bolivia"+" "+Bolivia/10+"%");
console.log("Colombia"+" "+Colombia/10+"%");
console.log("Guyana"+" "+Guyana/10+"%");
console.log("Suriname"+" "+Suriname/10+"%");
console.log("French Guiana"+" "+FrenchGuiana/10+"%");
