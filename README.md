# Vimpor Plugin

**Descrição Completa**
O Vimpor é um plugin leve, funcional e personalizável que permite aos jogadores informarem quem os convidou ao servidor, recompensando-os automaticamente. Com esse sistema, você pode impulsionar o crescimento da sua comunidade premiando aqueles que mais indicam amigos.
Ideal para servidores que desejam crescer de forma orgânica, premiar o engajamento dos jogadores e manter um controle seguro sobre convites.

# Funcionalidades
✅ Comando de convite simples: /vimpor convite <nick>

✅ Sistema de recompensa automática ao convidado (configurável no config.yml)

✅ Ranking com os 3 jogadores que mais convidaram via /vimpor toplist

✅ Consulta de convites com /vimpor check [nick]

✅ Comandos administrativos para reset individual ou global

✅ Totalmente traduzido e personalizável via mensagens.yml

✅ Armazenamento local seguro (convites.yml e usados.yml)

# Instruções de Instalação
Faça o download do plugin Vimpor.jar
Coloque o arquivo na pasta /plugins do seu servidor
Reinicie ou use /reload no servidor
O plugin irá gerar automaticamente os arquivos:
config.yml
mensagens.yml
convites.yml
usados.yml
Edite config.yml e mensagens.yml conforme sua necessidade
Pronto! Os jogadores já podem usar o sistema de convites

# Compatibilidade
✅ Spigot / Paper / Purpur / forks compatíveis
Testado nas versões: 1.19 até 1.20.1+
Sem dependências externas

️# Licença & Créditos
Plugin desenvolvido por @GabrielBk
Distribuição livre, desde que com os devidos créditos.

# Comandos
/vimpor convite <nick> ➜ Cadastre quem chamou o jogador

/vimpor check [nick] ➜ Mostra quantos convites o jogador tem

/vimpor toplist ➜ Mostra o ranking de indicados

/vimpor reset <nick> ➜ (Admin) Redefinir os dados de um jogador

/vimpor resetpl ➜ (Admin) Limpar todos os dados

/vimpor reload ➜ (Admin) Recarregar configurações e mensagens

**mensagens.yml**
Contém todas as mensagens que o plugin usa.
Suporta cores com & e placeholders como {nick}, {qtd}, {top1}, {top2}, {top3}.

**config.yml**
*dinheiro-comando: "money give {player} 150"*

Você pode alterar o comando para qualquer sistema (pontos, moedas, VIPs, etc).
Use {player} para o nome do jogador e {quantia} se quiser dinamizar a recompensa.


✅ [Vimpor Plugin](https://www.spigotmc.org/resources/vimpor-plugin.127463/field?field=documentation) **(Atualizado)**
