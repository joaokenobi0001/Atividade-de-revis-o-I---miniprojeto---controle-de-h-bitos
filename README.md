## Descrição do Aplicativo

Aplicativo simples para gerenciar hábitos diários. Permite visualizar uma lista de hábitos, marcar quais foram concluídos e editar a descrição de cada um. Foi desenvolvido em Flutter para consolidar conceitos como gerenciamento de estado, navegação entre telas e programação assíncrona.

## Funcionalidades Implementadas

- Lista de hábitos com checkbox para marcar conclusão.
- Ao marcar, o texto é riscado e muda de cor (feedback visual).
- Carregamento inicial simulado com `Future.delayed` e `async/await`.
- Duas telas:
  - **HomeScreen**: exibe a lista de hábitos.
  - **HabitDetailsScreen**: permite visualizar e editar a descrição do hábito.
- Navegação entre telas com `Navigator.push` e retorno de dados atualizados.
- Gerenciamento de estado local com `setState`.
- Armazenamento dos hábitos em uma lista de objetos `Habito`.
