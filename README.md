fun main() {
    
    var n1 = 2
    var n2 = 4
    
    println("☺ ******************---------******************☺")
    println("**                                            **")
    println("**                                            **")
    println("**             Minha Calculadora!!            **")
    println("**                                            **")
    println("** Adição entre $n1 e $n2                         **")
    println("** O resultado da adição é: " + (n1 + n2))
    println("**                                            **")
    println("** Subtração entre $n1 e $n2                      **")
    println("** O resultado da subtração é: " + (n1 - n2))
    println("**                                            **")
    println("** Multipliocação entre $n1 e $n2                 **")
    println("** O resultado da multiplicação é: " + (n1 * n2))
    println("**                                            **")
    println("** Divisão entre $n1 e $n2                        **")
    println("** O resultado da divisão é: " + (n1 / n2))
    println("**                                            **")
    println("**                                            **")
    println("**••••••••••••••••••••••••••••••••••••••••••••**")
    
    //wen - quando
    //
    // quando uma determinada condição for verdadeiro,outra determinada
    // ação será executada
    // 
    // Estrutura do when:
    // 
    // when(var){
    // valor -> ação
    // maisUm -> ação
    // outro -> ação
    // else -> ação
    // }
    // 
    var mes = 2
    
    when(mes){
        1 ->println("Acapulco - MEX")
        2 ->println("Paris - FRA")
        3 ->println("Berlim - ALE")
        4 ->println("Monaco - MON")
        5 ->println( "Pequim - CHI")
        6 ->println("Acre - BRA")
        7 ->println("Roma - ITA")
        8 ->println("Antenas - GRE")
        9 ->println("Madrid - ESP")
        10 ->println("Manchester - ING")
        11 ->println("Dubai - EAU")
        else ->println("São paulo - BRA")
    
}
println(mes)   
   
   
   
