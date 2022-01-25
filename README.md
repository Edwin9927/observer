# Observer
Example of the observer pattern adapted from the book Head First Design Patterns

![Image txt](https://github.com/Edwin9927/observer/blob/master/UML.png)

Usando el código de ejemplo de la estación de monitorio de clima, añade un observador (HeatIndexDisplay) que informe sobre el índice de calor, genere el informe correspondiente.
La función para calcular el índice de calor está dada por:


    heatindex =  16.923 + 
                  1.85212 * 10^-1  * T + 
                  5.37941 * RH - 
                  1.00254 * 10^-1  * T * RH + 
                  9.41695*10^-3 * T^2  + 
                  7.28898 * 10^-3 * RH^2 + 
                  3.45372 * 10^-4 * T^2 * RH - 
                  8.14971 * 10^-4 * T * RH^2 + 
                  1.02102 * 10^-5 * T^2 * RH^2 - 
                  3.8646 * 10^-5 * T^3 + 
                  2.91583 * 10^-5 * RH^3 + 
                  1.42721 * 10^-6 * T^3 + 
                  1.97483 * 10^-7 * T * RH^3 - 
                  2.18429 * 10^-8 * T^3 * RH^2 + 
                  8.43296 * 10^-10  * T^2 * RH^3 - 
                  4.81975 * 10^-11 * T^3 * RH^3

Ejecución:

![Image txt](https://github.com/Edwin9927/observer/blob/master/Captura%20de%20Pantalla%202022-01-25%20a%20la(s)%2000.13.39.png)
