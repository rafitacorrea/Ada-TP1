le dijiste uwu a mi novia????<br/>
ndeahhhhh<br/>
PIO!<br/>

para que baje a cada sección de manera sensual:
html{
scroll-behaviour:smooth;
}


Lore: recordar ponerle al nav z-index:1;

Comparto acá el código de la flechita que sube porque paja hacer un branch para eso
html: (va arriba de todo)
    <!-- Arrow -->
    <a href="#header"><div class="arrow">
        <i class="fas fa-arrow-up"></i>
       </div></a>
Sass:
// Arrow
.arrow{
    @include flex-row;
    width:45px;
    height:45px;
    border-radius:50%;
    background-color:$secondary-color;
    position:fixed;
    bottom:15px;
    right:15px;
    z-index:1;
}
.fa-arrow-up{
    font-size:25px;
    color:#fff;
    margin:0 auto;

}
