# Spray Light - O Mundo É Sua Tela

**Spray Light**, veja seu grafite ganhar vida com **Realidade Aumentada**!
[![Group 15](https://github.com/user-attachments/assets/cb137d95-99d7-4ad9-8c25-8ffd71a8aa03)](https://apps.apple.com/br/app/spray-light/id6737986180?l=en-GB)

Vivemos em um espaço que está cada vez mais sendo tomado por prédios altos, céus cinzas e multidões andando de um lado para o outro, onde todas essas pessoas estão sempre ocupadas em algum tipo de "**piloto automático**."

No meio de toda essa monotonia, existe o _grafite_. É uma arte feita para ser vista e apreciada, mas muitos grafiteiros lutam para ganhar reconhecimento e acabam sendo vistos negativamente pela sociedade, apesar de terem o papel simples e bonito de alegrar o dia de alguém.

Então, em um esforço para redefinir como a sociedade vê o _grafite_ e quebrar a rotina do "_piloto automático_", criamos o **Spray Light**.

## O que é Spray Light?

Com o **Spray Light**, você pode espalhar _grafite_ pelos muros da cidade, tornando possível visualizá-los usando **Realidade Aumentada**. Cada grafite que você coloca deixa um **marcador** no **mapa** para ajudá-lo a lembrar onde você postou. Quando você se aproximar e ativar o modo AR, você poderá vê-los.

Com isso, nosso objetivo é:
- **Mudar** a percepção marginalizada que a sociedade tem do _grafite_ 
- **Encorajar** o surgimento de novos grafiteiros, inicialmente apresentando sua arte em **forma virtual**!

[**Spray Light está disponível para download na App Store!**](https://apps.apple.com/br/app/spray-light/id6737986180)

---

## Minha Contribuição no Projeto

Como desenvolvedor, fui responsável por diversos aspectos técnicos e criativos do projeto:

### Desenvolvimento Técnico
- **Persistência de Dados**: Implementação do sistema de salvamento local utilizando **SwiftData**, além de testes com **CloudKit** para sincronização em nuvem (funcionalidade não incluída na versão de produção)
- **Interfaces**: Desenvolvimento das interfaces do aplicativo utilizando **SwiftUI**, focando em experiência do usuário e responsividade
- **Sistema de Mapas**: Implementação do sistema de **MapPins** utilizando **MapKit** e **CoreLocation** para exibir marcadores no mapa quando grafites são postados em localizações específicas
- **Realidade Aumentada**: Testes e implementação de funcionalidades do **ARKit**, incluindo experimentação com **ARWorldMap** para persistência de objetos AR no ambiente físico
- **Arquitetura**: Estruturação da arquitetura do projeto seguindo o padrão **MVVM**, garantindo manutenibilidade e escalabilidade do código

### Ideação e Pesquisa
- Participação ativa na **ideação do projeto** desde o conceito inicial
- Condução de **pesquisas** para identificação e validação da problemática relacionada à percepção social do grafite
- Colaboração no desenvolvimento da proposta de solução e definição de funcionalidades

---

## Tecnologias Utilizadas

- **SwiftUI**: Para o desenvolvimento da UI geral do app
- **RealityKit & ARKit**: Para gerenciar processos envolvendo toda a dinâmica de Realidade Aumentada, como postagem, translação, rotação de objetos, criação de novas entidades e outras tarefas
- **MapKit & CoreLocation**: Para exibição de mapas e gerenciamento de localização geográfica, permitindo a criação de marcadores nos locais onde grafites foram postados
- **SwiftData & DTO**: Para salvar grafites localmente e usar Data Transfer Objects (DTO) para transferência segura de dados via app usando Sendables
- **UIKit**: Usado para iniciar ARView em UIViewRepresentables
- **TipKit**: Para melhorar a experiência do usuário e fornecer orientação sobre alguns recursos durante o uso do app

---

## Versões de Teste (Não Disponíveis no MVP)

- **CloudKit**: Testes de compartilhamento de ARWorldMap baseado em nuvem

---

## Habilidades de Desenvolvimento

- Arquitetura MVVM
- SwiftUI
- ECS para Entidades ARKit
- Conventional Commits (Git)

---

### Autores

- [Jaide Fernando de Carvalho Zardin](https://github.com/JaideZrdn)
- [Pedro Larry](https://github.com/larry4us)
- [Isadora Cristina](https://www.linkedin.com/in/isadora-cristina-farias-bastos-9a992b219/)
