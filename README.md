# ACT_2_ADAN_ESCOBEDO_github_Codigo_s-ondasenoidal
Codigo en MATLAB codigo creacion de señal de onda senoidal.
Se analiza la libreria para ejecutar el codigo en MATLAB, se comienza realziando la estructura de la grafica con los ejes x , y linspace y sus valores estructurados x , y label , x,y ticks y como titulo es Señal Senoidal. 

x = linspace(0,10,100);
y = sin(x);

plot(x, y, 'LineWidth', 2)
xlabel('x')
ylabel('y')
title('Señal Senoidal')
legend('y = sin(x)')
xticks(0:2:10)
yticks(-1:0.5:1)
grid on
