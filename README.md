# lendo-listas
lendo listas de notas de alunos

alunos = ["José", "Joana", "Maria", "Carla", "Mauricio", "Andre", "Tiago", "Enzo", "Amanda", "Alessandra"]

notas = [
    [10, 9, 8, 8],
    [9, 7, 6, 4],
    [10, 10, 10, 10],
    [5, 3, 10, 9],
    [7, 6, 6, 6],
    [7, 7, 8, 7],
    [7, 7, 7, 9],
    [8, 5, 6, 7],
    [10, 9, 7, 4],
    [10, 1, 3, 3],
]

medias = []
for i in range(len(notas)):
    media = sum(notas[i])/ len(notas[i])
    medias.append(media)
    print(alunos[i], f'Média: {media}')
    
contador = 0    
for media in medias:
    if media >= 7:
        contador += 1
        
print(f'{contador} alunos tiveram a nota maior ou igual a 7')

![image](https://github.com/Victor-Antonio-Santos/lendo-listas/assets/160191987/fca65c95-96ee-4a38-a901-4116631dd32c)

