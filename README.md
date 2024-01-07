- 👋 Hi, I’m @Niiel25
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Niiel25/Niiel25 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->class Helicoptero:
    def __init__(self, modelo, cor):
        self.modelo = modelo
        self.cor = cor
        self.velocidade = 0

    def decolar(self):
        print(f"{self.cor} helicóptero {self.modelo} decolando!")

    def voar(self, velocidade):
        self.velocidade = velocidade
        print(f"{self.cor} helicóptero {self.modelo} voando a {self.velocidade} km/h.")

    def pousar(self):
        print(f"{self.cor} helicóptero {self.modelo} pousando.")

# Exemplo de uso
meu_helicoptero = Helicoptero("Apache", "Verde")
meu_helicoptero.decolar()
meu_helicoptero.voar(200)
meu_helicoptero.pousar()
