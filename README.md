# Atividade-PILHA
AULA SEXTA-FEIRA


if expressão[x] == "[":
    pilha.append("[")

if expressão[x] == "{":
    pilha.append("{")

if expressão[x] == ")":
    if len(pilha) > 0:
        topo = pilha.pop(-1)
    else:
        pilha.append(")")  # Força a mensagem de erro
        break

if expressão[x] == "]":
    if len(pilha) > 0:
        topo = pilha.pop(-1)
    else:
        pilha.append("]")  # Força a mensagem de erro
        break

if expressão[x] == "}":
    if len(pilha) > 0:
        topo = pilha.pop(-1)
    else:
        pilha.append("}")  # Força a mensagem de erro
        break

x = x + 1
