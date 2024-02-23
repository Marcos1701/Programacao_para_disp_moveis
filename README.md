# Programacao_para_disp_moveis

```javascript
class Pessoa {
    String nome;
    int idade;
    double altura;
  
  Pessoa(this.nome, this.idade, this.altura);
  
  void falar(String msg){
    print('$nome falou: \n $msg');
  }
}


void main() {
  Pessoa p = new Pessoa("Manoel Gomes", 56,1.60);
  p.falar("Olha, se você não me ama, então não me lige e nem fique me fazendo queixa..");
}
```
