# PostContenido 1 - Unidad 10

## Pruebas de Software en Aplicaciones Web

### Autor

Camilo Sánchez

### Descripción del Proyecto

Este proyecto corresponde al laboratorio PostContenido 1 de la Unidad 10 de Programación Web.

El objetivo principal es implementar una suite de pruebas automatizadas para una aplicación Spring Boot de gestión de tareas utilizando:

* JUnit 5
* Mockito
* Spring Boot Test
* MockMvc
* DataJpaTest
* JaCoCo

La aplicación permite gestionar tareas y validar el correcto funcionamiento de las diferentes capas mediante pruebas unitarias e integración.

---

## Estructura del Proyecto

```text
src
├── main
│   ├── java
│   │   └── com.universidad.tareas
│   │       ├── controller
│   │       ├── model
│   │       ├── repository
│   │       └── service
│   └── resources
│
└── test
    └── java
        └── com.universidad.tareas
            ├── service
            ├── controller
            └── repository
```

---

## Ejecución del Proyecto

### Ejecutar todas las pruebas

```bash
mvn test
```

### Ejecutar limpieza y pruebas

```bash
mvn clean test
```

### Generar reporte JaCoCo

```bash
mvn clean test jacoco:report
```

### Verificar cobertura mínima

```bash
mvn clean test jacoco:check
```

---

## Conclusiones

Se implementó una suite completa de pruebas automatizadas utilizando JUnit 5, Mockito y Spring Boot Test. Además, se configuró JaCoCo para medir la cobertura del código, garantizando una cobertura mínima del 70% y mejorando la calidad y confiabilidad de la aplicación.
