# PalmVein V2 — O que fazer
*Lista de ação · sem teoria, só execução*

---

## 🔴 CORRIGIR (erros — fazer primeiro)

**1. Texto quebrado no slider de setores**
Painel "Um dispositivo" está com texto corrompido.
→ Trocar por: *"Do balcão ao autoatendimento, o mesmo hardware lê a palma e aprova o pagamento. Sem periférico extra, sem integração complexa."*

**2. "Objetos se perdem" está duplicado**
Aparece 2x com corpos diferentes na seção de problema.
→ Deixar só uma versão: *"Cartão e celular podem ser esquecidos, roubados ou clonados."*

**3. "Match aprova o token" (card O3)**
→ Trocar para: **"Correspondência aprova o token"**

**4. Ano da estatística Serasa divergente**
Seção de problema (sem ano) vs. bloco de dados ("2024 · Serasa 2025").
→ Padronizar: dado de 2024, publicado pela Serasa Experian em 2025. Usar a mesma forma nas duas menções.

**5. Cards redundantes voltaram** (seção "Os benefícios que sustentam a confiança")
→ REMOVER: "Inalterável e interna" e "Sub-segundo" (já ditos no scanner e na tabela)
→ MANTER: "Homologação Anatel" + "Cadastro vitalício" + outros diferenciais únicos

**6. Links quebrados no rodapé**
→ Prioridade: **Privacidade** e **LGPD** (não podem estar mortos num site de segurança)
→ Depois: Sobre, Fundadores, Imprensa, Contato, Anatel

---

## 🟡 VERIFICAR (conferir ao vivo no Vercel)

**7. Slider de casos de uso** — confirmar que rotaciona as 5 cenas (piscina, cafeteria, hotel, parque, indústria) e não travou na indústria.

**8. WhatsApp** — confirmar que o link `wa.me` abre de verdade, com mensagem pré-preenchida.

**9. Formulário de contato** — confirmar que ao trocar de aba (Demonstração / Já sou cliente / Parcerias) o subtítulo, os campos e o botão realmente mudam. Se não mudam ainda, implementar.

**10. Passo 3 mobile** — conferir se o painel B2C ("você usa em segundos") não corta linha em tela pequena.

---

## 🟢 DEFINIR (depende de você / clientes)

**11. Marcas "biometria do futuro"** — hoje só Mastercard. Definir com os clientes quais outras logos entram.

**12. Formulário por aba** — decidir para onde vai cada envio (Demonstração → comercial / Já sou cliente → suporte / Parcerias → institucional).

**13. Campos da aba "Já sou cliente"** — trocar "Região" por Empresa/CNPJ + nº de série. Botão vira "ABRIR CHAMADO".

---

## 🏷️ SISTEMA DE TAGS (nova implementação)

Padronizar as tags que já existem soltas ("para empresas", "PARA VOCÊ", etc.) em um sistema único.

**Regra:**
- Uma tag no topo de cada **seção principal** (não em cards)
- Sempre em CAIXA ALTA
- Cor por público: **AZUL** = técnico/empresa · **VERDE** = experiência/B2C

**Tag sugerida por seção:**

| Seção | Tag | Cor |
|---|---|---|
| Passo a passo (Simples assim) | COMO COMEÇAR | Verde |
| Scanner (a mão) | COMO FUNCIONA | Azul |
| Casos de uso (slider cenas) | ONDE USAR | Verde |
| Benefícios/confiança | POR QUE CONFIAR | Azul |
| Problema (fundo preto) | O PROBLEMA | Azul |
| Setores (grid) | PARA CADA SETOR | Azul |
| Slider hardware | O PRODUTO | Azul |
| Tabela comparativa | COMPARATIVO | Azul |
| Segurança | SEGURANÇA | Azul |
| Hardware | HARDWARE | Azul |
| Dados de mercado | O MERCADO | Azul |
| FAQ | DÚVIDAS | Azul |
| Contato | FALE CONOSCO | Verde |

*Ajustar os nomes ao seu gosto — o que importa é: uma por seção, CAPS, cor por público.*

---

## Ordem sugerida de execução

1. Correções 1–5 (rápidas, texto)
2. Correção 6 (links rodapé)
3. Verificações 7–10 (teste ao vivo)
4. Sistema de tags
5. Itens 11–13 (conforme fechar com clientes)
