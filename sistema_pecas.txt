let peso_peca_gramas = 110;
var nomepecanova = "Mar";
let tamanhonome = nomepecanova.length;
let caixapecas_01 = [];
let capacidadecaixa_01 = caixapecas_01.length;
//checar se tem espaço na caixa>checar se tem peso suficiente>checar se o nome da peça tem +3 caracteres
if (capacidadecaixa_01 >= 10) {
    ("não há mais espaço na caixa, pegue uma nova.")
} else {
    if (peso_peca_gramas >= 100 && tamanhonome > 3){
        console.log('peça cadastrada');
        caixapecas_01.push(nomepecanova);
        console.log(caixapecas_01);
    } else {
        console.log('Não foi possível fazer o cadastro, verifique se a peça atende aos requisitos de peso e nome necessários');
    }
}