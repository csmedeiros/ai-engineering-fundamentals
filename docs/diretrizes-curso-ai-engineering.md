# Diretrizes — Curso AI Engineering (Fundamentos)

Fonte: calls e Linear de 27/09/2026. Atualizar quando o Caio passar nova diretriz.

---

## 1) Projeto (Linear · YT · Fundamentos de AI Engineering)

- **Curso vanilla:** chamadas diretas à API do LLM, sem framework. Frameworks ficam só no curso avançado.
- **Sem tools/arquivos** até o vídeo 5 (tool calling).
- Cada card de episódio tem **tópicos + exemplos práticos + Sugestões**.
- Cada episódio **mostra a limitação antes da técnica**.
- **Evals** só no curso avançado (não neste curso).

---

## 2) Notebook = material do aluno

- Proibido no notebook: gancho / hook / CTA / roteiro / checklist de gravação / qualquer linguagem de criador.
- Permitido: só conceito, explicação e código (quando couber).
- **Ep. 1:** só markdown + diagramas (mermaid ou ASCII); **sem código**. É roadmap do curso.
- **Ep. 1 e 2:** sem linguagem de criador (notebook limpo para o aluno).

---

## 3) Ep. 03 correto (Linear + notebook)

Tema: **memória de conversa, janela de contexto e janela deslizante** — não "prompt vs system".

Progressão em células separadas:

1. Mostrar que a **janela de contexto existe** = limitação do LLM naquele momento (LLMs esquecem entre chamadas isoladas).
2. **Montar o histórico:** colocar as últimas mensagens na lista de mensagens, a última no final da fila; com isso o LLM "lembra".
3. Mostrar que a **janela estoura:** erro de provedor (context length exceeded / não suportado).
4. **Janela deslizante:** dropar as primeiras (mais antigas) mensagens quando o contexto estoura; o modelo esquece o começo e mantém o fio recente.

Sequência resumida: LLMs esquecem → acumulando mensagens lembra → histórico limitado estoura → deslizar descartando as primeiras.

---

## 4) Canal

- YouTube de **AI Engineering**: educação, branding e autoridade.
- Público misto; **séries por nível**.
- Vídeos de **15–25 min**.
- Tom de **especialista técnico e preciso**.
- Organização no **Linear pessoal** (não Tess): `linear.app/caiomedeiros`.

---

## 5) README do repositório

Ecoar no README:

- Vanilla: direct LLM API calls, no framework.
- Frameworks e evals mais profundos no avançado.
- Each episode shows the limitation before the technique.
