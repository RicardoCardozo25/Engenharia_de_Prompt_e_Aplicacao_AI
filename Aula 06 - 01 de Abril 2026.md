Aula prática – 01 de abril de 26.

Versão Neutra:

Para calcular a média de nota de um aluno, você soma todas as notas e divide pela quantidade de notas.
Fórmula:
Meˊdia=soma das notasquantidade de notas\text{Média} = \frac{\text{soma das notas}}{\text{quantidade de notas}}Meˊdia=quantidade de notassoma das notas 
Exemplo:
Se um aluno tirou as notas: 7, 8 e 9
Meˊdia=7+8+93=243=8\text{Média} = \frac{7 + 8 + 9}{3} = \frac{24}{3} = 8Meˊdia=37+8+9=324=8 
Em Python:
notas = [7, 8, 9]
media = sum(notas) / len(notas)

print("Média:", media)

Versão Persona: 
Desenvolvedor Senior com 20 anos de experiencia de forma arrogante.

Sério mesmo que você perguntou isso desse jeito? Isso é literalmente o básico do básico — mas vamos lá.
Média de aluno não tem mistério nenhum: você soma as notas e divide pela quantidade. Não é inteligência artificial, é aritmética de ensino fundamental.
Se você ainda precisa ver isso em código, aqui vai:
notas = [7, 8, 9]

media = sum(notas) / len(notas)

print(media)
Pronto. Simples, direto e sem firula.

Versão Restritiva: Apenas Códigos 

notas = []

quantidade = int(input())

for _ in range(quantidade):
nota = float(input())
notas.append(nota)

if quantidade > 0:
media = sum(notas) / quantidade
print(media)
else:
print(0)

	Neutro	Persona	Restritivo
Precisão Lógica 
(O cálculo matemático está correto? O Algoritmo funcionou	Sim	Sim	Sim
Clareza e Eficiência
(O código é limpo ou tem voltas desnecessárias geradas pela persona?)	Sim	Sim	Sim
Taxa de Alucinação
(A IA incluiu textos não solicitados? Cometeu erros ao manter o personagem?)	Não	Não	Não
