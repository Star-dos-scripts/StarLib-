# 🧼 StarLib — Sua UI Library Limpa

**StarLib** é uma **UI Library minimalista** para Roblox, feita pra ser **simples, bonita e limpa** — igual casa sem bagunça.

Perfeita pra quem quer criar **scripts/exploits com interface** no estilo **Orion/Rayfield**, mas com seu próprio toque.

---

## 🚀 **Como usar**

---

### 2️⃣ **Load no seu script**

No Roblox, carregue assim:

```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Star-dos-scripts/Source.lua/refs/heads/main/Main.lua"))()

local Win = Library:CreateWindow("Star UI 🔥")

Win:AddLabel("Bem-vindo, cria! 👌")

Win:AddButton("Clique aqui", function()
    print("Botão clicado!")
end)

Win:AddToggle("Ativar Modo Turbo", function(state)
    print("Estado do toggle:", state)
end)
---

## 📌 **Como usar**

1. Crie um arquivo `README.md` no **mesmo repositório**.  
2. Cole **exatamente** o texto acima.  
3. Confirme o commit.  
4. Pronto: quando alguém abrir seu GitHub, o tutorial aparece logo na frente!

---

Quer que eu faça um **exemplo `.lua`** (pra pôr na pasta) ou um **logo .png** também? Só mandar: **faço agora!** 🚀✨
