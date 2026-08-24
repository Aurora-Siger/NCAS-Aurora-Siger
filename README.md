# NCAS - Núcleo Cognitivo da Aurora Siger

Sistema de apoio à decisão desenvolvido para a colônia marciana Aurora Siger, capaz de armazenar, organizar, consultar e interpretar informações operacionais utilizando arquivos texto, arquivos JSON, regras lógicas e prompts estruturados.

> Projeto da Fase 5 — "Inteligência Artificial no Comando"

---

## 📌 Sobre o projeto

Com o crescimento da colônia Aurora Siger, a quantidade de dados gerados (alertas operacionais, logs, registros de manutenção, solicitações da tripulação) aumentou rapidamente, tornando a análise manual insuficiente.

O **NCAS** nasce como um protótipo de núcleo cognitivo: uma ferramenta de apoio — não um substituto dos especialistas humanos — capaz de:

- Armazenar registros importantes da colônia
- Recuperar informações salvas em arquivos
- Organizar dados em formato JSON
- Aplicar validações lógicas em solicitações operacionais
- Simplificar regras booleanas utilizadas no sistema
- Estruturar prompts para simular interações com IA generativa
- Apoiar a geração de respostas organizadas e padronizadas
- Considerar aspectos éticos, sociais e de diversidade no uso da tecnologia

---

## 🛠️ Tecnologias utilizadas

- **Python 3** (biblioteca padrão apenas — sem frameworks externos)
- Manipulação de arquivos texto (`open`, `read`, `readline`, `readlines`, `writelines`, `with`)
- **JSON** para dados estruturados
- **Álgebra booleana** e simplificação (Teoremas de Simplificação / De Morgan)
- **Prompt Engineering** (zero-shot, few-shot, saída estruturada) — simulação de IA generativa

---

## 📂 Estrutura do repositório

```
NCAS-Aurora-Siger/
├── codigo_fonte.py           # Código principal do sistema
├── dados_colonia.json        # Dados estruturados utilizados pelo sistema
├── registros_colonia.txt     # Registros, logs e informações salvas em texto
├── regras_logicas.pdf        # Expressão booleana, simplificação e explicação
├── prompts_utilizados.pdf    # Prompts criados e explicação de cada um
├── link_video.txt            # Link do vídeo de apresentação (YouTube - Não listado)
└── README.md
```

---

## ▶️ Como executar

```bash
git clone https://github.com/<usuario>/NCAS-Aurora-Siger.git
cd NCAS-Aurora-Siger
python codigo_fonte.py
```

Não são necessárias bibliotecas externas — apenas Python 3 instalado.

---

## ⚙️ Funcionalidades do sistema

- [ ] Menu de navegação no terminal
- [ ] Cadastrar registros da colônia
- [ ] Consultar registros salvos
- [ ] Carregar e salvar dados em JSON
- [ ] Executar validação lógica (regra booleana simplificada)
- [ ] Exibir prompts estruturados
- [ ] Simular resposta de um assistente inteligente

**Exemplo de fluxo:** ao selecionar "Analisar alerta operacional", o sistema carrega um alerta salvo em JSON, verifica se é crítico usando a regra booleana simplificada e exibe um prompt estruturado com uma resposta padronizada ao centro de controle.

---

## 🧮 Lógica do sistema

O sistema utiliza pelo menos uma regra lógica para tomada de decisão, representada como expressão booleana e simplificada com base nos Teoremas de Simplificação ou De Morgan. Detalhes completos em [`regras_logicas.pdf`](./regras_logicas.pdf).

---

## 🤖 Simulação de IA generativa

O núcleo cognitivo simula uma interação com um assistente inteligente por meio de prompts estruturados (zero-shot, few-shot e saída estruturada), sem exigir integração real com uma API de IA. Detalhes completos em [`prompts_utilizados.pdf`](./prompts_utilizados.pdf).

---

## ⚖️ Ética, diversidade e responsabilidade

O projeto inclui uma reflexão sobre uso responsável de sistemas inteligentes: riscos de respostas enviesadas, importância da diversidade no desenvolvimento, cuidado com linguagem discriminatória, impactos sociais de decisões automatizadas e responsabilidade humana no uso de IA generativa.

---

## 🎥 Vídeo de apresentação

Link disponível em [`link_video.txt`](./link_video.txt).

---

## 👥 Equipe

| Nome | Responsabilidade |
|---|---|
| _(preencher)_ | Dados e arquivos (JSON/texto) |
| _(preencher)_ | Código Python |
| _(preencher)_ | Lógica booleana |
| _(preencher)_ | Prompts e ética |

---

## 📋 Requisitos técnicos

- Código executável sem bibliotecas avançadas ou frameworks externos
- Integração real com API de IA é opcional (se usada, deve ser explicada)
- Código organizado e comentado
