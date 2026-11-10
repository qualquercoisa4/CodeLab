# CodeLab

Plataforma estática de desafios de programação para estudantes.

## Trilhas
- **Godot / GDScript:** 20 desafios progressivos com editor executável incorporado da Coddy.
- **GameMaker / GML:** 20 desafios e exemplos para praticar no GameMaker instalado.

## Executar localmente
Abra `index.html` em um navegador moderno ou publique a raiz do repositório em um host estático, como Vercel.

## Editor Godot
O CodeLab incorpora `https://coddy.tech/embed-editor` com `lang=godot`. O código inicial de cada desafio é enviado por meio do parâmetro `code` em Base64 URL-safe. O editor e a execução são fornecidos pela Coddy; mantenha o crédito visível na interface.

O embed é gratuito segundo a documentação pública da Coddy: https://coddy.tech/embed/pt?editorLang=godot

## Progresso
O progresso e o XP são armazenados localmente no navegador via localStorage. Não há conta nem sincronização entre dispositivos nesta versão.

## Limitações conhecidas
- A execução Godot depende da disponibilidade do serviço externo Coddy e de conexão à internet.
- O editor incorporado recebe o código inicial ao abrir um desafio; não há integração documentada para ler de volta o conteúdo editado pelo iframe.
- A trilha GML oferece exercícios, mas não inclui compilador GameMaker dentro do site. A execução oficial requer o ambiente GameMaker.
