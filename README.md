# Trabalho-de-Conclusao-Curso
- Neste experimento, foi realizado o trabalho conjunto de dois frameworks, LangFlow e CrewAI.

- O LangFlow é um framework no-code, onde não se faz necessário o uso de código de programação, com o trabalho sendo realizado na construção de fluxograma através de blocos de componentes.

- O CrewAI é um framework para a criação de agentes de IA.

- O trabalho conjunto destes frameworks serviu para a criação de uma aplicação onde, um artigo será enviado, e um agente de IA irá analisar e criar um texto de sugestões de melhorias para este texto, e no fim, estas sugestões serão enviadas para o e-mail destinatário.

- Para a utilização deste projeto, baixe o arquivo TCC.json, e entre na plataforma do LangFlow, crie um projeto novo, de preferência em branco, e importe o projeto. Utilize suas API Keys para os componentes necessários, como o de Llm do Groq. Para o funcionamento do componente de enviar e-mail, altere o e-mail destinatário e abra o código do componente, dentro dele, coloque um e-mail remetente e crie uma senha de app para este e-mail, sendo ele de plataforma gmail.

- Upe um artigo, de preferência pdf, de até 10 páginas (caso seja maior, irá estourar os tokens da Llm do Groq gratuita), e clique no botão de start lá no componente de enviar e-mail. Caso o processo ocorra de maneira perfeita, as sugestões serão enviadas no e-mail destinatário correto.
