Exception 
Ex.

Красим в красный все пункты списка, кроме последнего элемента и кроме тех, у которых есть класс .active:
li:not(:last-child):not(.active) {
  color: red;
}

