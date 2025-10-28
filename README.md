# Calculadora de IMC Flutter 🧮📱

App mobile para calcular o **IMC** com visual moderno e intuitivo. Mostra o valor calculado e destaca automaticamente a **categoria correspondente**.

---

## 🔹 Funcionalidades

- Entrada de **altura** (cm) e **peso** (kg)
- Seleção de **gênero** (visual apenas)
- Cálculo do IMC com **categoria**
- Tela de **categorias**, destacando automaticamente a do usuário
- Layout moderno: cartões, cores suaves, cantos arredondados

---

## 🎬 Demonstração

**Exemplo de cálculo:**

![Tela principal do app](imagens/tela_principal.png)

**Categorias com destaque:**

![Categorias do IMC](imagens/categorias_imc.png)

> Para GIF, substitua a imagem pelo arquivo `.gif`:
```markdown
![App em ação](imagens/demo_imc.gif)


🧮 Como funciona

IMC = peso / (altura em metros)²

Categorias:

Categoria	Faixa de IMC
Abaixo do peso	< 18.5
Peso normal	18.5 – 24.9
Sobrepeso	25 – 29.9
Obesidade Grau I	30 – 34.9
Obesidade Grau II	35 – 39.9
Obesidade Grau III	≥ 40


⚡ Instalação:
git clone https://github.com/seu-usuario/imc_flutter_app.git
cd imc_flutter_app
flutter pub get
flutter run

🛠 Tecnologias

Flutter & Dart

Google Fonts

Material Design

🎨 Melhorias futuras

Animação ao abrir categorias, destacando a do usuário

Interpretação personalizada por gênero ou idade

Histórico de IMCs

Suporte a unidades imperiais
