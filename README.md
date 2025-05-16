## ChatMEI: Seu Assistente Inteligente para MEIs e Negócios Sustentáveis

A inspiração para o ChatMEI surgiu durante um desafio da Imersão IA da Alura, onde a paixão por tecnologia se uniu a uma necessidade real observada no dia a dia. Como contador, tenho a oportunidade de ajudar muitas pessoas a transformarem seus sonhos em negócios. Nessa jornada, percebi que, embora o Microempreendedor Individual (MEI) seja uma porta de entrada fantástica para o empreendedorismo, muitos iniciam suas atividades inspirados por outros, mas sem um conhecimento claro sobre as importantes responsabilidades e os detalhes da gestão de um MEI.

Foi pensando em desmistificar esse universo e oferecer um primeiro apoio prático e acessível que o ChatMEI  foi idealizado. Ele nasceu do desejo de ver mais empreendedores começando com o pé direito, com mais informação e confiança.

O objetivo do ChatMEI é ser aquele parceiro inicial que conversa de forma simples sobre como abrir e gerir um MEI, especialmente com um olhar para negócios sustentáveis, ajudando a transformar boas ideias em empreendimentos conscientes e bem estruturados desde o começo.

## Principais Funcionalidades do ChatMEI

* **Gera Ideias de Negócios Sustentáveis:** Ajuda a pensar em negócios criativos e com foco em sustentabilidade.
* **Auxilia na Validação Inicial de Ideias:** Orienta sobre os primeiros passos para testar uma ideia de negócio.
* **Dá Dicas de Práticas Sustentáveis:** Oferece conselhos para tornar um negócio mais amigo do meio ambiente e da sociedade.
* **Orienta MEIs (Microempreendedores Individuais):** Explica de forma simples noções básicas sobre finanças, impostos (como o DAS e a Declaração Anual) e até sobre a contratação do primeiro funcionário, sempre lembrando da importância de consultar um contador.
* **Analisa Imagens:** Pode receber fotos de produtos, rascunhos ou inspirações e dar um feedback construtivo no contexto do empreendedorismo sustentável.
* **Ajuda no Planejamento:** Guia o usuário passo a passo para criar um "Esboço de Mini Plano de Negócios Sustentável", que pode ser baixado como um arquivo de texto.
* **Conversa Amigável:** Tudo isso em uma conversa com linguagem simples, clara e encorajadora!

## Tecnologias Utilizadas

* **Python:** Como a linguagem de programação principal.
* **API Gemini do Google:** Especificamente o modelo `models/gemini-2.0-flash` para a inteligência do chatbot.
* **Biblioteca Cliente Google para Python:** Para interagir com a API Gemini (utilizando `from google import genai` e `client = genai.Client()`).
* **Google Colab:** Como ambiente para desenvolver e rodar o ChatMEI.

## Para conversar com o ChatMEI, siga estes passos

**Pré-requisitos:**  * Você precisará de uma Conta Google para usar o Google Colab e a API Gemini.
**Obtenha uma Chave de API (API Key) do Google Gemini:**  * Acesse o site [Google AI for Developers](https://ai.google.dev/) (ou procure por "Google Gemini API Key").

  ** Siga as instruções para criar sua chave de API gratuita. Guarde essa chave em um local seguro.**

**Configure a API Key no Google Colab:**
  * Abra o notebook do ChatMEI no Google Colab.
  * Na barra lateral esquerda do Colab, clique no ícone de chave (🔑) chamado "Secrets".
  * Clique em "Adicionar um novo secret".
  * No campo "Nome", digite exatamente: `GOOGLE_API_KEY`
  * No campo "Valor", cole a sua chave de API que você obteve do Google.
  * Certifique-se de que a opção "Acesso do notebook" está ativada para este secret.
   
**Execute o Notebook:**
  * Com o notebook aberto no Colab, você pode executar todas as células de uma vez clicando em "Ambiente de execução" no menu superior e depois em "Executar tudo".
  * Aguarde as células serem processadas. A primeira vez pode levar um tempinho para o cliente ser inicializado.
  * ChatMEI deverá se apresentar e então você poderá começar a conversar!

**Dependências (Bibliotecas Adicionais):**
Este projeto foi desenvolvido para rodar no Google Colab. As bibliotecas Python utilizadas (google.genai, google.genai.types) para interagir com a API Gemini do Google geralmente já estão disponíveis no ambiente padrão do Colab e não requerem instalação manual adicional com !pip install.


![Image](https://github.com/user-attachments/assets/ab508b2a-0b4f-4597-b210-88fd275e4043)

  
Desenvolvido por: **Erick Elber Borges Rodrigues**

* LinkedIn: [erick-borges-238737131](https://www.linkedin.com/in/erick-borges-238737131/)
* GitHub: [ErickElber](https://github.com/ErickElber)
