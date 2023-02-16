# Programacion-basica-java
En este repositorio podrás encontrar lo realizado en Programación básica de la U fidelitas durante el primer cuatrimestre del 2023

/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */
package com.demo.proyecto_intro_progra;

import javax.swing.JOptionPane;

/**
 *
 * @author Brandon
 */
public class Proyecto_intro_progra {

    public static void main(String[] args) {
        final int regDesarrolladores = 0;
        final int regRequerimientosBacklog = 1;
        final int regInteraciones = 2;
        final int asignacionTrabajo = 3;
        final int cierreInteracion = 4;
        final int reportes = 5;
        final int SALIR = 6;

        String[] opciones = {
            "1. Registrar a los desarrolladores",
            "2. Registrar los requerimientos en Backlog",
            "3. Registrar los registros de iteraciones",
            "4. Registrar la asignación de trabajo",
            "5. Registrar la asignación de trabajo",
            "6. Registrar el cierre de una iteración",
            "7. Abrir el módulo de reportes",
            "8. Salir"
        };

        int seleccion = JOptionPane.showOptionDialog(null, "Por favor selecciona la opción que desees realizar:",
                "Menú de opciones", JOptionPane.DEFAULT_OPTION, JOptionPane.INFORMATION_MESSAGE, null, opciones,
                opciones[0]);

        switch (seleccion) {
            case regDesarrolladores:
                // código para registrar desarrolladores
                break;
            case regRequerimientosBacklog:
                // código para registrar requerimientos
                break;
            case regInteraciones:
                // código para registrar iteraciones
                break;
            case asignacionTrabajo:
                // código para registrar asignación de trabajo
                break;
            case cierreInteracion:
                // código para cerrar una iteración
                break;
            case reportes:
                // código para abrir el módulo de reportes
                break;
            case SALIR:
                // salir del programa
                break;
            default:
                // opción no válida
                break;
        }
    }
}
