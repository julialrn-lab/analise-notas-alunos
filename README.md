alunos = {
    "Ana": 8,
    "João": 5,
    "Maria": 7,
    "Pedro": 4
}

for nome, nota in alunos.items():
    if nota >= 6:
        print(f"{nome} está aprovado com nota {nota}")
    else:
        print(f"{nome} está reprovado com nota {nota}")
