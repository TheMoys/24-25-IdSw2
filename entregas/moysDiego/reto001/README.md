# Legibilidad

<table>
<tr>
<th>

### 🔰 Asignatura

</th>
<th>

### 🔰 Enlace al repo.

</th>
</tr>
<tr></tr>
  <tr>
    <td valign=top>
        EDA 1
    </td>
    <td valign=top>
        <a href="https://github.com/TheMoys/23-24-eda1">Enlace al repo</a>
    </td>
  </tr>
  <tr>
    <td valign=top>
        Programacion II
    </td>
    <td valign=top>
        <a href="https://github.com/TheMoys/progra2-22-23">Enlace al repo</a>
    </td>
  </tr>
  <tr>
    <td valign=top>
        Ninety Seven Hearts (proyecto del colegio)
    </td>
    <td valign=top>
        <a href="https://github.com/Diego024/ninety-seven_hearts_PRUEBA">Enlace al repo</a>
    </td>
  </tr>
  <tr>
    <td valign=top>
       Examen final de Programacion I
    </td>
    <td valign=top>
        <a href="https://github.com/TheMoys/22-23-prg1-examenfinal">Enlace al repo</a>
    </td>
  </tr>
  <tr>
    <td valign=top>
       Examen parcial de Programacion I
    </td>
    <td valign=top>
        <a href="https://github.com/TheMoys/PRG1-22-23-ExamenParcial">Enlace al repo</a>
    </td>
  </tr>
</table>

## CODE SMELLS...

### 1. Nombrado
|||
|-|-|
|Nombres ambiguos en los métodos. ¿Delete qué? ¿Insert qué? |[Código](https://github.com/TheMoys/23-24-eda1/blob/685e14fddb5c1ec04b383f5467c927da4b5fe3c2/entregas/moysDiego/reto-003/List.java#L14)|

### 2. Comentarios

|||
|-|-|
|Comentarios que no aportan nada al código ya que los nombres de los métodos son los suficientemente explicativos.| [Código](https://github.com/TheMoys/progra2-22-23/blob/dca3c7d73cbc4b9b78d651fb58b62e48d99572b6/ejercicios/entregas/diegoMoys/EX001PooStudent/src/Subject.java#L67)|
|Comentarios sin sentido.| [Código](https://github.com/TheMoys/progra2-22-23/blob/dca3c7d73cbc4b9b78d651fb58b62e48d99572b6/ejercicios/entregas/diegoMoys/EX001PooStudent/src/Subject.java#L31)|

### 3. Formato
|||
|-|-|
|Exceso de identación dentro del código.| [Código](https://github.com/Diego024/ninety-seven_hearts_PRUEBA/blob/f9d0c03d7647f4292af97a0336005e165753b6f5/app/api/dashboard/administradores.php#L65)|

### 4. Estandares
|||
|-|-|
|Indecisión en el nombrado de modelos. ¿Singular o plural?| [Código](https://github.com/Diego024/ninety-seven_hearts_PRUEBA/blob/f9d0c03d7647f4292af97a0336005e165753b6f5/app/models/administradores.php#L6)|
|Misma pregunta... ¿Singular o plural?| [Código](https://github.com/Diego024/ninety-seven_hearts_PRUEBA/blob/f9d0c03d7647f4292af97a0336005e165753b6f5/app/models/catalogo.php#L5)|

### 5. Consistencia
|||
|-|-|
|Ejemplo de que muchas veces ponerse de acuerdo para hacer algo no siempre es la mejor opción, imprimir un html en php debería ser un pecado capital...| [Código](https://github.com/Diego024/ninety-seven_hearts_PRUEBA/blob/f9d0c03d7647f4292af97a0336005e165753b6f5/app/helpers/private_page.php#L3)|

### 6. Codigo muerto
|||
|-|-|
|Main innecesario, en este ejemplo, la clase pasó directamente a los test sin necesidad de pasar por Main.| [Código](https://github.com/TheMoys/progra2-22-23/blob/dca3c7d73cbc4b9b78d651fb58b62e48d99572b6/ejercicios/entregas/diegoMoys/EX000PooIntroduction/src/Main.java#L1)|

### 7. DRY
|||
|-|-|
|Exceso de elseif, se pudo haber resulto con pocos elseif con condicionales OR.| [Código](https://github.com/TheMoys/22-23-prg1-examenfinal/blob/08fcf3be594dc7a32ccf84cdbe94cd082a9001c0/Pacman.java#L57)|

### 8. YAGNI
|||
|-|-|
|Imprimir esta variable es completamente innecesario para le ejecución del codigo, únicamente sirve con fines de control pero no debería estar ahí en la entrega final.| [Código](https://github.com/TheMoys/PRG1-22-23-ExamenParcial/blob/12bbb0cdb4bdfb4794423d8042f701961f03f86d/entregas/moysDiego/parcialDiegoMoys.java#L46)|