# Ios
CourseraIOS



//: Playground - noun: a place where people can play

import UIKit

let rango = 0...100
let rangoDos = 30...40


for indice in rango{
    
    if (indice % 5) == 0{
        print("el número es:\(indice) Bingo!!!")
        
    }
    
    if (indice % 2) == 0{
        print("el número es:\(indice) par!!!")
    }
    
    if (indice % 2) != 0{
        print("el número es:\(indice) impar!!!")
    }
    
    
    if indice >= 30 && indice <= 40{
        print("el número es:\(indice) Viva Swift!!!")
    }
    
    
    
}




