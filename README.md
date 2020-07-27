# Mathlad

[asy]
/* Geogebra to Asymptote conversion, documentation at artofproblemsolving.com/Wiki go to User:Azjps/geogebra */
import graph; size(8cm); 
real labelscalefactor = 0.5; /* changes label-to-point distance */
pen dps = linewidth(0.7) + fontsize(10); defaultpen(dps); /* default pen style */ 
pen dotstyle = black; /* point style */ 
real xmin = -12.55, xmax = 19.23, ymin = -9.24, ymax = 7.52;  /* image dimensions */
pen rvwvcq = rgb(0.08235294117647059,0.396078431372549,0.7529411764705882); pen sexdts = rgb(0.1803921568627451,0.49019607843137253,0.19607843137254902); 

draw((-6.01,3.98)--(-7.43,-1.7)--(1.39,-1.56)--cycle, linewidth(2) + rvwvcq); 
 /* draw figures */
draw((-6.01,3.98)--(-7.43,-1.7), linewidth(2) + rvwvcq); 
draw((-7.43,-1.7)--(1.39,-1.56), linewidth(2) + rvwvcq); 
draw((1.39,-1.56)--(-6.01,3.98), linewidth(2) + rvwvcq); 
draw((-6.878235294117647,0.5070588235294117)--(-3.02,-1.63), linewidth(1.2) + sexdts); 
draw((-4.194959907128713,2.621172687228794)--(-3.02,-1.63), linewidth(1.6) + sexdts); 
draw((-4.194959907128713,2.621172687228794)--(-7.43,-1.7), linewidth(1.6)); 
draw((-6.878235294117647,0.5070588235294117)--(1.39,-1.56), linewidth(1.2)); 
draw((-6.01,3.98)--(0.9553332239001964,4.090560844823813), linewidth(1.6)); 
draw((0.9553332239001964,4.090560844823813)--(-4.949117647058824,-0.5614705882352942), linewidth(1.2)); 
draw(circle((-5.980597609561753,2.127649402390439), 1.8525839352180455), linewidth(1.6)); 
 /* dots and labels */
dot((-6.01,3.98),dotstyle); 
label("$A$", (-5.93,4.18), NE * labelscalefactor); 
dot((-7.43,-1.7),dotstyle); 
label("$B$", (-7.35,-1.5), NE * labelscalefactor); 
dot((1.39,-1.56),dotstyle); 
label("$C$", (1.47,-1.36), NE * labelscalefactor); 
dot((-3.02,-1.63),linewidth(4pt) + dotstyle); 
label("$M$", (-2.95,-1.48), NE * labelscalefactor); 
dot((-5.951195219123505,0.27529880478087637),linewidth(4pt) + dotstyle); 
label("$D$", (-5.87,0.44), NE * labelscalefactor); 
dot((-4.194959907128713,2.621172687228794),linewidth(4pt) + dotstyle); 
label("$E$", (-4.11,2.78), NE * labelscalefactor); 
dot((-6.878235294117647,0.5070588235294117),linewidth(4pt) + dotstyle); 
label("$F$", (-6.79,0.66), NE * labelscalefactor); 
dot((-4.949117647058824,-0.5614705882352942),linewidth(4pt) + dotstyle); 
label("$L$", (-4.87,-0.4), NE * labelscalefactor); 
dot((-3.607479953564357,0.495586343614397),linewidth(4pt) + dotstyle); 
label("$K$", (-3.53,0.66), NE * labelscalefactor); 
dot((0.9553332239001964,4.090560844823813),linewidth(4pt) + dotstyle); 
label("$T$", (1.03,4.26), NE * labelscalefactor); 
clip((xmin,ymin)--(xmin,ymax)--(xmax,ymax)--(xmax,ymin)--cycle); 
 /* end of picture */
[/asy]
