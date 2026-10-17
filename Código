alunos = int(input("Digite a quantidade de alunos: "))
monitores = int(input("Digite a quantidade de monitores: "))
convidados = int(input("Digite a quantidade de convidados: "))

total_pessoas = alunos + monitores + convidados

if total_pessoas > 100:
    print(f"\n❌ Evento inválido! O total de pessoas ({total_pessoas}) ultrapassa o limite de 100 ingressos.")
elif convidados > 20:
    print(f"\n❌ Evento inválido! O número de convidados ({convidados}) ultrapassa o limite máximo permitido de 20.")
else:
    ingressos_sobrando = 100 - total_pessoas
    print("\n✅ Tudo pronto! O evento pode ser realizado.")
    print(f"Total de participantes: {total_pessoas}")
    print(f"Ingressos restantes: {ingressos_sobrando}")
