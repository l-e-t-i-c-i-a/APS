Código UML:

@startuml

left to right direction

actor "Usuário Comum" as UC
actor "Administrador da Comunidade" as AC
actor "Membro da Comunidade" as MC
actor "Visitante" as V
actor "Patrocinadores/Parceiros" as PP
actor "Administrador do Sistema" as AS

UC <|-- AC
UC <|-- MC
UC <|-- V
UC <|-- PP

usecase "Criar eventos" as UC001
usecase "Realizar backup de dados" as UC002
usecase "Enviar notificações" as UC003
usecase "Gerenciar membros" as UC004
usecase "Gerar relatórios de participação" as UC005
usecase "Cadastrar-se na plataforma" as UC006
usecase "Visualizar e se inscrever em eventos" as UC007
usecase "Configurar perfil" as UC008
usecase "Buscar eventos anteriores" as UC009
usecase "Ver regras de participação" as UC010
usecase "Baixar relatórios de participação" as UC011
usecase "Buscar membros/eventos" as UC012
usecase "Visualizar informações públicas" as UC013
usecase "Promover anúncios" as UC014
usecase "Obter informações sobre alcance de anúncios" as UC015
usecase "Gerenciar autenticação de usuários" as UC016
usecase "Realizar backup dos dados dos usuários" as UC017
usecase "Habilitar login via Google" as UC018
usecase "Notificar usuários sobre atualizações" as UC019
usecase "Visualizar regras de privacidade" as UC020
usecase "Alterar e-mail" as UC021
usecase "Alterar senha" as UC022
usecase "Ativar autenticação de dois fatores" as UC023
usecase "Criptografar senhas" as UC024
usecase "Reportar problemas" as UC025
usecase "Receber notificações sobre manutenções" as UC026
usecase "Ler informações no idioma desejado" as UC027

AC --> UC001
AC --> UC002
AC --> UC003
AC --> UC004
AC --> UC005
MC --> UC006
MC --> UC007
MC --> UC008
MC --> UC009
MC --> UC010
MC --> UC011
MC --> UC012
V --> UC013
PP --> UC014
PP --> UC015
AS --> UC016
AS --> UC017
AS --> UC018
AS --> UC019
UC --> UC020
UC --> UC021
UC --> UC022
UC --> UC023
UC --> UC024
UC --> UC025
UC --> UC026
UC --> UC027

@enduml
