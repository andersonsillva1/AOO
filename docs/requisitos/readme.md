# Sistema de Conexão de Jogadores por Interesse

## Problema que o Sistema Resolve
Jogadores que têm dificuldade para encontrar outros gamers com interesses semelhantes, horários compatíveis e preferência pelos mesmos jogos.

## Público-Alvo
- Jogadores de console, PC e mobile.

## Funcionalidades
- Chat entre jogadores
- Envio de convites para partidas
- Sistema de busca por jogadores compatíveis
- Sugestão de amigos conforme estilo de jogo e plataforma

---

## Requisitos Funcionais (RF)

- **RF01** - Cadastro de usuário com nome, e-mail, plataforma, jogos preferidos, estilo de jogo e horários.
- **RF02** - Login e logout com autenticação segura.
- **RF03** - Edição e visualização de perfil de jogador.
- **RF04** - Sugestão automática de jogadores compatíveis (matchmaking).
- **RF05** - Busca manual com filtros (jogo, plataforma, região, estilo, etc.).
- **RF06** - Chat por texto entre jogadores.
- **RF07** - Envio e recebimento de convites para jogar.
- **RF08** - Notificações sobre mensagens, convites e novas sugestões.
- **RF09** - Avaliação de jogadores após partidas.
- **RF10** - Bloqueio de jogadores indesejados.

---

## Requisitos Não Funcionais (RNF)

- **RNF01** - Sugestões devem ser geradas em menos de 2 segundos.
- **RNF02** - Interface amigável e adaptada para desktop e mobile.
- **RNF03** - Segurança com autenticação e criptografia de dados.
- **RNF04** - Suporte a grande número de usuários (escalável).
- **RNF05** - Disponibilidade de 99,9% do tempo.
- **RNF06** - Compatível com diferentes dispositivos e navegadores.

---

## Regras de Negócio (RN)

- **RN01** - Convites só podem ser enviados após interação prévia via chat.
- **RN02** - Jogadores mal avaliados têm menor prioridade nas sugestões.
- **RN03** - Jogadores bloqueados não aparecem em buscas ou sugestões.
- **RN04** - Horários de disponibilidade devem aparecer quando logado e definido como disponivel pelo usuario.
- **RN05** - Cada jogador pode selecionar seus estilos de jogos principais.

---

> *Ideia inspirada na dificuldade de encontrar novos parceiros de jogo quando amigos antigos param de jogar.*

