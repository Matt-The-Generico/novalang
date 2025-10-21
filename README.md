# Atualização EM BREVE

### **Estamos trabalhando na nlang V5!**

#### Features:

1. 🧩 Condicionais completas
```
else if <condição>:
    ...
else:
    ...
```
🔹 Isso permite múltiplas verificações em sequência.
```
if x > 10:
    print("Maior que 10")
else if x == 10:
    print("Igual a 10")
else:
    print("Menor que 10")
```
2. 🔁 Mais tipos de loop

    while condição: — repete enquanto a condição for verdadeira.

    for <variável> in lista: — percorre listas, intervalos, etc.

    repeat until condição — repete até algo se tornar verdadeiro.
   
🔹 Exemplo:
```
let i = 0
while i < 10:
    print(i)
    i = i + 1
```
3. ⚙️ Operadores lógicos

    and, or, not
    🔹 Permite expressões condicionais mais ricas:
```
if idade >= 18 and possui_carteira:
    print("Pode dirigir")
```
4. 🚦 Controle de fluxo

Permitir interromper ou continuar loops:

    break — sai do loop

    continue — pula pro próximo ciclo

🔹 Exemplo:
```
loop:
    let x = input()
    if x == "sair":
        break
```
5. 🧠 Coleções (listas e dicionários)

Para manipular dados mais complexos.

➡️ Listas:
```
let frutas = ["maçã", "banana", "uva"]
print(frutas[1])
```
➡️ Dicionários (ou tables):
```
let pessoa = {
    nome: "Mateus",
    idade: 17
}
print(pessoa.nome)
```
6. 💬 Entrada de dados
```
let nome = input("Digite seu nome: ")
print("Olá, " + nome)
```
7. ⚡ Tratamento de erros

```

try:
    let x = 10 / 0
catch:
    print("Erro ao dividir")
finally:
    print("Fim da execução")
```
