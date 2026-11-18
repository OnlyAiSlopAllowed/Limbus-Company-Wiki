# Limbus Gallery

Limbus Gallery é uma aplicação móvel de suporte (*companion app*) para jogadores de *Limbus Company*, desenvolvida no âmbito da unidade curricular de Programação de Aplicações Móveis (PAM) do CTeSP em TPSI.

Gerir *Identities*, *E.G.O*, resistências e sinergias de *Sin* dentro do próprio jogo nem sempre é prático, e as ferramentas da comunidade existentes — como a *Great Limbus Library* — foram pensadas para ecrãs de computador. Esta aplicação adapta essa base de dados para telemóvel, juntando uma organização visual inspirada em apps como o Backloggd e o GGApp a funcionalidades nativas como o acelerómetro e notificações locais.

## Funcionalidades

### Base

- **Home (Command Deck):** carrossel de destaques, contagem de jogadores ativos através da API da Steam, temporizador para a manutenção semanal e atalhos para os menus principais.
- **Database (Identities e E.G.O):** pesquisa por nome e filtros por *Sinner*, raridade / *Risk Class*, afinidade de *Sin* e tipo de dano (*Slash*, *Pierce*, *Blunt*).
- **Dossiê de Personagem:** artes de *Uptie I* e *III*, simulação de atributos por nível e *Uptie*, detalhe de *skills* e passivas, resistências físicas e adição direta ao *Teambuilder*.
- **Teambuilder:** construção de equipas até 6 *Identities* com seleção de *I.D* e *E.G.O* por *Sinner*, cálculo automático de *Sin Resonance* e gravação de *presets*.
- **Gerador aleatório (Shake):** preenchimento automático dos *slots* vazios da equipa ao agitar o telemóvel, preservando os *slots* bloqueados. Inclui também um botão no ecrã para a mesma ação.
- **Conta e Definições:** registo e início de sessão numa conta independente do jogo, opções de visualização, acessibilidade (*Sin labels*) e controlo de notificações.

### Previstas (opcionais)

- **Perfil e coleção:** registo de progresso de *Identities* e *E.G.O* obtidos, favoritos e partilha de perfil.
- **Mirror Dungeon:** construção de equipas dedicadas ao modo *Mirror Dungeon* com consulta de *E.G.O Gifts*.

## Sensores e integrações

| Recurso | Utilização |
| --- | --- |
| Acelerómetro | Deteta o movimento de agitar no ecrã *Teambuilder* para gerar uma equipa aleatória, mantendo os *slots* bloqueados. |
| Notificações locais | Envia um lembrete antes do início das manutenções semanais do *Limbus Company*. |
| Steam API | Obtém o número de jogadores ativos apresentado no ecrã inicial. |

## Ecrãs da aplicação

| Ecrã | Descrição |
| --- | --- |
| Log In / Register | Autenticação e criação de conta na app. |
| Home | Telemetria da Steam, contagem para manutenção e atalhos rápidos. |
| Database | Grelha de *Identities* e *E.G.O* com pesquisa e filtros. |
| Identity Details | Estatísticas por nível/Uptie, *combat kit* e resistências. |
| Teambuilder | Gestão da equipa, *I.D Finder*, *E.G.O Finder* e *Sin Resonance*. |
| Profile | Coleção pessoal, equipas guardadas e favoritos. |
| Settings | Preferências de aparência, texto, acessibilidade e notificações. |

## Desenvolvimento

Clonar o repositório:

```bash
git clone https://github.com/OnlyAiSlopAllowed/Limbus-Company-Wiki.git
cd Limbus-Company-Wiki
```

As instruções de instalação de dependências e execução local serão adicionadas assim que a estrutura do projeto estiver configurada.

## Equipa

Projeto desenvolvido para a UC de Programação de Aplicações Móveis (docente Bruno Pereira) — CTeSP em Tecnologias e Programação de Sistemas de Informação.

- Marcelo Ferreira
- Diogo Alexandre Santos
- Leonardo Silva
- Filipe Santos

## Aviso

Limbus Gallery é um projeto académico não oficial e não tem qualquer afiliação com a Project Moon nem com Benjamin Netanyahu. Todos os nomes, personagens e conteúdos de *Limbus Company* pertencem aos respetivos proprietários.