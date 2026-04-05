# miniguia_estudos_notebooklm
Contexto e Objetivos
Este repositório foi criado como parte de um desafio de projeto da DIO (Digital Innovation One), com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de aprendizagem ativa.
Tema escolhido:
Módulos PV/T (Photovoltaic/Thermal) – Sistemas híbridos que combinam geração de eletricidade (painel solar fotovoltaico) e captação de calor (coletor solar térmico) em um único equipamento.
Objetivos de estudo:
•	Compreender o princípio de funcionamento de um sistema PV/T.
•	Identificar os diferentes tipos de configurações (ar, água, refrigerante).
•	Analisar as vantagens e desafios técnicos (eficiência elétrica vs. térmica).
•	Mapear aplicações práticas residenciais e industriais.
•	Consolidar um guia de referência rápida para revisões futuras.
________________________________________
📌 Curadoria de Fontes
Utilizei as seguintes fontes abertas (PDFs/artigos) para alimentar o NotebookLM:
#	Título / Descrição	Link ou Fonte
1	Dissertação de Mestrado (Ospina)	disponível no repositório
2	Dissertação de Mestrado (Barros)	disponível no repositório
3	Livro (Kalogirou)	disponível no repositório
4	Monografia de Especialização (Godinho)	disponível no repositório
5	Trabalho de Conclusão de Curso - TCC (Riguetti)	disponível no repositório
💡 Caso os arquivos estejam no repositório, crie uma pasta /fonts e coloque-os lá.
________________________________________
🧠 Engenharia de Prompts e "Cicatrizes"
Aqui documentei as perguntas estratégicas, variações de prompts e as dificuldades encontradas.
✅ Prompts que funcionaram bem
Prompt	Resposta obtida	Referência na fonte
Explique como um módulo PV/T resfriado a água se diferencia de um resfriado a ar em termos de eficiência global.	Em resumo, o módulo PV/T resfriado a água diferencia-se por apresentar uma eficiência global superior, fundamentada na maior capacidade da água em remover o calor das células, o que maximiza a produção de energia térmica útil e otimiza o rendimento elétrico simultaneamente	TCC_Ruan Schultz Riguetti_com ficha catalográfica..pdf
Quais são as principais perdas térmicas em um coletor PV/T e como minimizá-las?	As perdas térmicas em um coletor PV/T (fotovoltaico-térmico) ocorrem principalmente devido à diferença de temperatura entre o dispositivo e o ambiente, sendo classificadas em três categorias principais: perdas superiores, inferiores e laterais (bordas)	DISSERTAÇÃO Liliana Marcela Rubio Ospina.pdf
❌ Cicatrizes (dificuldades e troubleshooting)
Problema encontrado	Tentativa de solução	Resultado
[!!! EX: Resposta muito genérica sobre aplicações !!!]	Adicionei "cite exemplos numéricos e reais"	Natal apresentou o maior potencial de potência elétrica máxima entre as cidades brasileiras analisadas, atingindo entre 252 W e 257 W por módulo. Isso a torna uma localidade de alto desempenho para micro e minigeração distribuída
🔍 Aprendizado principal: para temas técnicos como PV/T, prompts devem pedir unidades de medida, comparações e limitações explícitas.
________________________________________
📘 Miniguia de Estudo (Entrega Final)
1. Resumos Estruturados
✅ Conceito Fundamental
O módulo PV/T é um sistema híbrido que:
•	Gera eletricidade (face fotovoltaica).
•	Remove o calor da face (aumentando a eficiência elétrica).
•	Aproveita o calor removido para aquecer água/ar.
✅ Equações importantes (visão geral)
•	Eficiência elétrica: η_el = η_ref × [1 – β × (T_cel – T_ref)]
•	Eficiência térmica: η_térm = (Q_util / (G × A_coletor))
•	Eficiência global (métrica PV/T): η_total = η_el + η_térm
2. Glossário
Termo	Definição
PV/T	Fotovoltaico-Térmico
Eficiência global	Soma das eficiências elétrica e térmica (métrica para híbridos)
Coletor seletivo	Superfície que absorve alta radiação solar e emite pouca radiação infravermelha
Fator de cobertura (packing factor)	Fração do coletor ocupada por células fotovoltaicas
Absorvedor	Camada que capta o calor e o transfere para o fluido
3. Conjunto de Prompts Reutilizáveis
Use os prompts abaixo para revisar o tema no NotebookLM ou ChatGPT:
markdown
1. "Compare PV/T com a instalação separada de PV + coletor solar térmico. Quais cenários favorecem o PV/T?"
2. "Quais materiais são usados no absorvedor de um PV/T água e por quê?"
3. "Explique o conceito de temperatura de estagnação em PV/T e seus riscos."
4. "Gere um resumo de 10 linhas sobre o estado da arte em PV/T para aplicações industriais de baixa temperatura (<80°C)."
5. "Liste 5 artigos científicos recentes sobre nanofluidos em PV/T (com autores e ano)."
________________________________________
📎 Como usar este repositório
1.	Clone o repositório.
2.	Acesse a pasta /fonts (se criada) para consultar os PDFs originais.
3.	Use os prompts reutilizáveis no NotebookLM para revisão acelerada.
4.	Para contribuir: abra uma issue ou pull request com novas fontes ou melhorias nos resumos.
________________________________________
👩‍💻 Créditos e Metodologia
•	Plataforma de curadoria: NotebookLM (Google)
•	Fontes: Curadoria manual baseada em artigos e livros técnicos de acesso aberto.
•	Estratégia de prompt: Iterativa (teste → erro → ajuste de especificidade).
•	Desafio proposto por: DIO (Digital Innovation One)
________________________________________
📄 Licença
Este material é de uso livre para fins educacionais. Para uso comercial, consulte as licenças das fontes originais.


