# Projeto Épico

## Objetivos
ao iniciar faça um quarto de adolecente de fundo e destaque um cigarro 
fume cigarro apertando o botão esquerdo do mouse antes da sua mãe chegar
cada clique no botão direito do moue significa um pouco a menos de cigarro
faça uma porta fechada no quarto 
e em tempos aleatorios faça a porta abrir revelando a mãe
caso sua mãe chegue pare tudo e troque a tela para um game over escrito "sua mãe te viu fazer fumaça"

### Stack Tecnlógico
- Backend: PHP estruturado com sessões nativas
- Banco de dados: MySQL (PDO para segurança)
- Frontend: HTML5, PHP, CSS, Tailwind CSS

#### Regras de negócio (CORE)

fumo secreto
aumento de pontos por fumo
encerramento em caso de flagrante

  

##### Regras Globais
- Use sempre PDO para conexão e queries no MySQL para evitar SQL Injections
- Mantenha o código limpo e comente apenas logicas complexas.
- Separe os arquivos de forma lógica: um arquivo para conexão com a base (bd.php) e scripts de backend isolados e views em HTML5/PHP, nunca faça o sistema como um monolito, deixe sempre separados todas as regras para facilitar os futuros upgrades.
 - Estilize as telas em Tailwind de forma responsiva priorizando o MobileFrist.
 - Retorne sempre as mensagens de erros de forma claras na interface para o usuário (TOAST)
 - sempre trate as mensagens de caixa de mensagens nativas do navegador em um MODAL
