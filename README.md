# prova
sei la, so pra fazer a prova da faculdade

                                            TRIANGULOS
const input = parseInt(prompt("Digite o primeiro lado do trângulo: "));
const input2 = parseInt(prompt("Digite o segundo lado do trângulo: "));
const input3 = parseInt(prompt("Digite o terceiro lado do trângulo: "));

if(!isNaN(input) && !isNaN(input2) && !isNaN(input3)){
    if(input + input2 > input3 && input + input3 > input2 && input3 + input2 > input){
        if(input === input2 && input === input3){
            alert("Este triângulo é equilátero!");
        }
        else if(input === input2 && input !== input3 || input3 === input2 && input3 !== input || input === input3 && input !== input2){
            alert("Este triângulo é isósceles!");
        }
        else if(input !== input2 && input !== input3){
            alert("Este triângulo é escaleno!");
        };
    }
    else{
        alert("Os valores informados não formam um triângulo!");
    };
}
else{
    alert("Algum dos valores enviados não é válido!");
};

                                              CONVERSOR DE NOTAS
const input = parseFloat(prompt("Digite um número de 0 a 100: "));

switch(true){
    case input > 100:
        alert("Nota inválida!");
        break;
    case input >= 90 && input <= 100:
        alert("Sua nota é A");
        break;
    case input < 90 && input >= 80:
        alert("Sua nota é B");
        break;
    case input < 80 && input >= 70:
        alert("Sua nota é C");
        break;
    case input < 70 && input >= 60:
        alert("Sua nota é D");
        break;
    case input < 60:
        alert("Sua nota é F");
        break;
    default:
        alert("Sua resposta não se encaixa nos números requisitados!");
};

                                                  TARIFA

const input = parseInt(prompt("Digite sua idade: "));
const input2 = prompt("É estudante? Responda com sim/não: ").toLowerCase();

if(input < 5){
    alert("Tarifa grátis!");
}
else if(input >= 60){
    alert("Tarifa reduzida!");
}
else if(input2 === "sim" || input2 === "s"){
    alert("Tarifa estudantil!");
}
else if(input >= 5 && input < 60 && input2 === "não" || input2 === "nao" || input2 === "n"){
    alert("Tarifa normal!");
}
else{
    alert("Alguma ou as duas respostas foram inválidas!");
}

                                                      DIAS
const input = parseInt(prompt("Digite um número de 1 a 7: "));

if(input > 0 && input <= 7){
    switch(input){
        case 1:
            alert("Domingo");
            break;
        case 2:
            alert("Segunda-feira");
            break;
        case 3:
            alert("Terça-feira");
            break;
        case 4:
            alert("Quarta-feira");
            break;
        case 5:
            alert("Quinta-feira");
            break;
        case 6:
            alert("Sexta-feira");
            break;
        default:
            alert("Sábado");
    };
}
else if(isNaN(input)){
    alert("Digite um número, ao invés de caractere!");
}
else{
    alert("Número inválido!");
};

                                                  AUMENTAR LETRAS
toUppercase

                                                  CONTAGEM DE CARACTERES
length
                                                  
