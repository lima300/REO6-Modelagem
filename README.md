# REO - Semana 6: Modelagem e implementação de software

_Este repositório foi criado com a finalidade de realizar a atividade
proposta pelo ***6º Roteiro de Estudos Orientados*** Da disciplina de Modelagem e implementação de software._

Abaixo temos um trecho de código que realiza classificação de alunos de acordo com suas notas em níveis de A a E,
escrito em python

```python
def main():
    notas_conceituais = {"A": 0, "B": 0, "C": 0, "D": 0, "E": 0}

    entrada = ""

    while entrada != "fim":
        entrada = str(input())
        if entrada != "fim":
            notas_conceituais[entrada] += 1
    mais_frequente = max(notas_conceituais, key=notas_conceituais.get)
    print(mais_frequente, end=" ")
    print(notas_conceituais[mais_frequente])


if __name__ == "__main__":
    main()
```

Agora temos uam listagem de tópicos

- Tópico 1
- Tópico 2
  - sub-tópico 2.1
- Tópico 3
- Tópico 4
