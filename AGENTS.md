# Diretrizes de Agentes - Duolingo Premium Low-Ticket 🦉

Este repositório contém a infraestrutura, landing pages, funis de conversão, materiais de entrega e criativos da operação **Duolingo Premium (Low-Ticket)**.

---

## 1. Visão Geral da Oferta

- **Nicho:** Educação / Idiomas / Infoproduto Low-Ticket.
- **Público-Alvo:** Estudantes, vestibulandos, concurseiros e pessoas comuns querendo aprender inglês/espanhol/francês sem gastar uma fortuna.
- **Dores Principais:**
  - Ter que esperar horas ou pagar quando acabam as 5 vidas / corações.
  - Anúncios irritantes e longos entre as lições que quebram o foco.
  - O preço oficial do Duolingo Super (mais de R$ 200/ano ou R$ 32/mês), inacessível para a maioria.
- **Proposta Única de Valor (UVP):** "Desbloqueie o Duolingo Super com Vidas Infinitas, Sem Anúncios e Acesso Total por um valor simbólico e único."

---

## 2. Precificação & Funil de Vendas

| Oferta | Preço | Posicionamento |
| :--- | :--- | :--- |
| **Plano Anual** | **R$ 10,00** | Entrada / barreira mínima de compra |
| **Plano Vitalício** | **R$ 27,00** | **Carro-chefe / Maior valor percebido (Ancoragem)** |
| *Order Bump Sugerido* | R$ 7,90 | Pack 1000 Frases Mais Usadas em Inglês + Flashcards Anki |
| *Upsell Sugerido* | R$ 19,90 | Grupo VIP Vitalício de Atualizações + Suporte Prioritário WhatsApp |

---

- **Logo Oficial do Projeto:**
  - Arquivo: [`assets/logo.png`](file:///home/wanderson/.t3/projects/duolingopro/assets/logo.png) (Coruja Duolingo com textura diamante/gradiente e coroa dourada imperial).
  - Referência original: [`assets/creative_ref.png`](file:///home/wanderson/.t3/projects/duolingopro/assets/creative_ref.png).
- **Os 5 Benefícios-Chave da Oferta:**
  1. **Sem Anúncios** (Foco 100% sem interrupções)
  2. **Modo Offline** (Estudar sem gastar dados móveis ou sem sinal)
  3. **Vidas Ilimitadas** (Treinar sem medo de errar e sem esperar horas)
  4. **Conversa com IA** (Prática de conversação inteligente nível Duolingo Max)
  5. **Treinos Personalizados** (Revisão cirúrgica de erros)
- **Cores Oficiais:**
  - Verde Duolingo: `#58CC02` (Hover / Borda 3D: `#46A302`)
  - Azul Elétrico: `#1CB0F6` (Hover / Borda 3D: `#1899D6`)
  - Amarelo Dourado: `#FFC800` (Hover / Borda 3D: `#E5A500`)
  - Vermelho Alerta: `#FF4B4B`
  - Roxo / IA Duolingo Max: `#9333EA`
  - Fundo & Neutros: `#FFFFFF`, `#F7F7F7`, `#E5E5E5`, `#4B4B4B`
- **Botões Estilo Duolingo ("Tactile 3D Buttons"):**
  - Botões arredondados com `border-b-4` em tom mais escuro.
  - Efeito `:active`: `translate-y-1` com redução da borda inferior para dar a sensação tátil de clique mecânico.
- **Tipografia:** Sans-serif arredondada, amigável e legível (`Nunito`, `DIN Round`, `Poppins` ou `system-ui`).

---

## 4. Estrutura de Entrega & Arquitetura Técnica

1. **Android:**
   - Entrega via APK Premium / Mod atualizado com sincronização com conta Duolingo ou acesso família.
   - Instruções em 3 passos: Baixar APK -> Habilitar fontes desconhecidas -> Fazer login com conta existente.
2. **iOS (iPhone/iPad):**
   - Método via perfil/configuração ou adesão a Plano Família gerenciado por automação/e-mail.
   - Passo a passo detalhado em vídeo ou tela gravada.
3. **Plataformas de Pagamento Recomendadas:**
   - Kiwify, Kirvano, Hotmart, PerfectPay ou Greenn com entrega imediata pós-PIX via e-mail e webhook na página de obrigado.

---

## 5. Instruções para Subagentes

Quando atuar em tarefas deste repositório:
- **Agente de Copy:** Foque em urgência ética, quebra de medos ("Vou perder meu progresso?" -> "Não, continua de onde parou!"), e destaque para as vidas infinitas.
- **Agente de Frontend:** Crie páginas ultra-leves (HTML sem frameworks pesados, Tailwind CDN ou compilado limpo), carregamento em menos de 1.5s em redes 4G/3G.
- **Agente de Tráfego/Criativos:** Organize hooks dinâmicos focando no drama do "Zero Corações" no meio de uma lição importante.
