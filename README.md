# 🎮 Loop Narrativo – Fantasia Sombria  
Protótipo desenvolvido como parte do exercício de criação de um **core loop narrativo** em um jogo de fantasia sombria, onde cada ação do jogador avança a história sem o uso de cutscenes.  
O objetivo é demonstrar como narrativa, mecânicas e mudança de estado do mundo podem operar em ciclos curtos e repetíveis.

---

## 📌 1. Objetivo do Exercício
Criar um loop jogável e sistemático que:

- Possua um **objetivo narrativo claro**
- Tenha **3 verbos centrais** em ciclos de 20–60s
- Altere o **estado do mundo** a cada repetição
- Utilize **feedback loops positivos e negativos**
- Mantenha **UI diegética** e narrativa emergente
- Mostre **3 ciclos completos** (vídeo final será atualizado após feedback)

---

## 🎯 2. Core Loop (Ciclo de Curto Prazo)
**Explorar → Coletar → Purificar → Mundo Reage**

### ✔ Explorar  
Jogador entra na névoa, aumentando corrupção e revelando sinais de presença inimiga.

### ✔ Coletar  
Fragmentos de memória são encontrados e absorvidos, revelando pedaços da história.

### ✔ Purificar  
Rituais dissipam parte da névoa, mas despertam criaturas e alteram comportamento de NPCs.

### ✔ Mundo Reage  
Após cada purificação, novas regras emergem: inimigos surgem, NPCs mudam atitude, áreas se tornam mais perigosas.

Diagramas do core loop estão em `/docs`.

---

## 🧱 3. Meta Loop (Médio Prazo)
Ao longo de 2–3 ciclos:

- A névoa se torna mais agressiva  
- Fragmentos revelam segredos incômodos  
- NPCs mudam comportamento (amizade/hostilidade)  
- Inimigos evoluem  
- O vilarejo se transforma visual e sistemicamente  

Material completo em `/docs`.

---

## 📖 4. Arco Narrativo
O jogador precisa purificar o vilarejo antes que seus habitantes percam completamente a memória.  
A névoa revela fragmentos de lembranças, expõe segredos perigosos e intensifica a ameaça a cada purificação.

Texto completo em:

👉 `/docs/arco-narrativo.md`

---

## 🎥 5. Protótipo em Vídeo
O vídeo demonstra **o Ciclo 1 completo**, com:

- Cena 1: Explorar  
- Cena 2: Coletar  
- Cena 3: Purificar  
- Cena 4: Mundo Reage  

Arquivo disponível em:

👉 `/prototipo/ciclo1.mp4`

Os ciclos 2 e 3 serão adicionados após feedback.

---

## 📁 6. Estrutura do Repositório

| Caminho | Conteúdo |
|--------|----------|
| `/docs` | Diagramas, narrativa e roteiro do vídeo |
| ├── `core-loop-diagram.png` | Diagrama do loop central |
| ├── `meta-loop-diagram.png` | Diagrama do meta loop |
| ├── `arco-narrativo.md` | Texto do arco narrativo |
| └── `roteiro-video.odt` | Roteiro usado para montagem do vídeo |
| `/assets` | Imagens e elementos visuais |
| ├── `backgrounds/` | Fundos da floresta e vilarejo |
| ├── `ui/` | Amuleto, barras e elementos de interface |
| ├── `criaturas/` | Fantasmas, sombras e inimigos |
| ├── `npc/` | Aldeões e personagens |
| └── `fragmentos/` | Memórias coletáveis |
| `/prototipo` | Vídeos dos ciclos do loop |
| └── `ciclo1.mp4` | Demonstração inicial do loop |
| `README.md` | Documentação geral do projeto |


---

## 🧩 7. Tecnologias Utilizadas

- **DaVinci Resolve 20** – montagem e efeitos simples  
- **Git e GitHub** – versionamento e entrega  
- **Geração de assets 2D** para prototipação visual   

---

## 🚀 8. Próximos Passos

- Finalizar Ciclo 2 e Ciclo 3 do vídeo  
- Ajustar áudio e reforçar feedback sonoro  
- Criar documentação complementar no PR    

---

## ✔ 9. Status do Projeto  
🟦 **Entrega parcial enviada para feedback**  
🟩 Ciclo 1 completo  
🟨 Ciclos 2 e 3 pendentes  
🟪 Documentação pronta  

---



