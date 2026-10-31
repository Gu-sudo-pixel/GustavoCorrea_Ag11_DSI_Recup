# GustavoCorrea_Ag11_DSI_Recup

#reservatório
cores = {
    1: "\033[91m",  # Vermelho
    2: "\033[93m",  # Amarelo
    3: "\033[92m",  # Verde
    4: "\033[96m",  # Ciano
    5: "\033[94m"   # Azul
}

reset = "\033[0m"

textos = {
    1: "muito baixo (crítico)",
    2: "baixo",
    3: "medio",
    4: "alto",
    5: "muito alto (alerta)"
}

print("Verifique o nível do reservatório: ")

nivel = int(input("1() 2() 3() 4() 5()"))
if nivel in cores:
    print(f"{cores[nivel]}N{nivel} = {textos[nivel]}{reset}")

else:
    print("resposta invalida")

