# Agenda Telefônica em Python
Este projeto é uma agenda telefônica desenvolvida em Python usando exclusivamente a orientação a objetos. O sistema permite cadastrar, editar, apagar e listar contatos, onde cada contato possui um nome e uma lista de telefones com tipos associados (residência, trabalho, fax, etc).

## Funcionalidades
- Adicionar novos contatos com nome e múltiplos telefones.
- Editar informações de contatos existentes.
- Remover contatos e telefones.
- Listar todos os contatos da agenda.
- Ordenar contatos por nome.
- Salvar e carregar a agenda em arquivos locais usando serialização (pickle).
- Interface de linha de comando (menu interativo) para facilitar o uso.

## Estrutura do Código
- Nome, Telefone, TipoTelefone: Classes que representam dados básicos da agenda.
- ListaUnica: Classe genérica para gerenciar listas que não permitem elementos duplicados.
- Agenda: Gerencia a coleção de contatos (DadoAgenda) e os tipos de telefone.
- AppAgenda: Classe principal que controla o fluxo do programa e interações com o usuário.
- Funções auxiliares para validação de entrada.

## Use o menu para navegar entre as opções:
- novo: Adicionar contato.
- altera: Alterar contato.
- apaga: Remover contato.
- lista: Mostrar contatos.
- grava: Salvar agenda em arquivo.
- le: Carregar agenda de arquivo.
- ordena: Ordenar contatos por nome.
- sair: Encerrar o programa.

## Requisitos
Python 3.x

## Observações
A agenda é salva e carregada em arquivos binários usando o módulo pickle.
A entrada do usuário é validada para garantir dados corretos.
É possível associar vários telefones a um contato, cada um com seu tipo.
