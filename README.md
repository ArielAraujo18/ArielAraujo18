# Bem-vindo(a) ao meu GitHub! 🚀

def bem_vindo(ariel: str) -> str:
    stack = ["Python", "Java", "SQL", "JavaScript"]  # Minhas linguagens favoritas!
    projetos = [
        "🎵 App de Música", 
        "🛒 Sistema de Vendas", 
        "📊 Análise de Dados"
    ]
    
    print(f"Olá, {ariel}! 👋")
    print("Aqui você encontrará alguns dos meus projetos em:")
    
    for linguagem in stack:
        print(f" - {linguagem}")

    print("\nSinta-se à vontade para explorar os seguintes projetos:")
    for projeto in projetos:
        print(f" - {projeto}")

    return "Espero que goste e contribua se puder! 😄"

if __name__ == "__main__":
    bem_vindo("visitante")
