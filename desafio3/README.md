1. O que colocar na Descrição (README.md)
Use este roteiro para estruturar o seu arquivo de texto principal:

📑 Título: Análise de Redes Sociais com Neo4j
Descrição: Este projeto demonstra o uso da linguagem Cypher e do banco de dados orientado a grafos Neo4j para mapear e analisar conexões em uma rede social. O foco é identificar influenciadores, sugerir conexões (amigos de amigos) e analisar interesses comuns.

🚀 Funcionalidades
Mapeamento de Influência: Identificação de usuários com maior número de seguidores.

Algoritmo de Recomendação: Sugestão de amizades baseada em conexões de segundo grau (Triadic Closure).

Análise de Caminhos: Cálculo do caminho mais curto entre dois usuários.

Performance Otimizada: Uso de índices e constraints para garantir consultas rápidas e integridade dos dados.

🛠️ Estrutura do Projeto
/scripts/01_schema.cypher: Definição de Constraints e Índices.

/scripts/02_seed.cypher: Carga de dados de exemplo.

/scripts/03_analysis.cypher: Consultas analíticas de rede.
