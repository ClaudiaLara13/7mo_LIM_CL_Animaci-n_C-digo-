# 7mo_LIM_CL_Animaci-n_C-digo-
Codigo de la animación de un cuadrado de 3*3

A=1
B=4

for Sum = 0 : 0.5 : 10
clf
    x=A+Sum
    x2=B+Sum

    plot([x x2], [1 1], "r-")
    hold on
    plot([x2 x2], [1 4], "r-")
    hold on
    plot([x2 x], [4 4], "r-")
    hold on
    plot([x x], [4 1], "r-")
    hold on
    axis equal;
    xlim([0 15]);
    ylim([0 5]);
pause(0.1)

end
