# Spray Light - O Mundo É Sua Tela

**Spray Light**, veja seu grafite ganhar vida com **Realidade Aumentada**!

[![Group 15](https://github.com/user-attachments/assets/cb137d95-99d7-4ad9-8c25-8ffd71a8aa03)](https://apps.apple.com/br/app/spray-light/id6737986180?l=en-GB)

[**Baixe Spray Light na App Store!**](https://apps.apple.com/br/app/spray-light/id6737986180)

---

## O que é? 

Vivemos em um espaço que está cada vez mais sendo tomado por prédios altos, céus cinzas e multidões andando de um lado para o outro, onde todas essas pessoas estão sempre ocupadas em algum tipo de "**piloto automático**."

No meio de toda essa monotonia, existe o _grafite_. É uma arte feita para ser vista e apreciada, mas muitos grafiteiros lutam para ganhar reconhecimento e acabam sendo vistos negativamente pela sociedade, apesar de terem o papel simples e bonito de alegrar o dia de alguém.  Essa percepção marginalizada afeta não apenas os artistas, mas também priva a sociedade de expressões culturais valiosas.

**Spray Light** é um aplicativo que permite espalhar _grafite_ pelos muros da cidade de forma virtual, tornando possível visualizá-los usando **Realidade Aumentada**. Em um esforço para redefinir como a sociedade vê o _grafite_ e quebrar a rotina do "_piloto automático_", nosso app age como uma ponte entre a arte de rua e a tecnologia, permitindo que artistas expressem sua criatividade sem barreiras físicas ou legais.

---

## Como Funciona

**Sistema de Realidade Aumentada:**
- Crie grafites virtuais e "pinte" paredes reais através da câmera do dispositivo
- Utilize ferramentas de **translação e rotação de objetos** para posicionar perfeitamente seu grafite
- Visualize seus grafites em **escala real** no ambiente físico através do modo AR
- Experimente com diferentes estilos e designs sem limitações físicas

**Sistema de Mapeamento:**
- Cada grafite que você coloca deixa um **marcador no mapa** utilizando **MapKit** e **CoreLocation**
- Relembre onde você postou suas obras
- Quando se aproximar de um local marcado, ative o modo AR para visualizar os grafites

**Persistência e Compartilhamento:**
- Seus grafites são salvos localmente usando **SwiftData**
- Sistema de **Data Transfer Objects (DTO)** garante transferência segura de dados entre telas
- Experimentação com **ARWorldMap** permite que objetos AR persistam no ambiente físico

---

## Minha Participação

### Desenvolvimento Técnico

**Persistência de Dados:**
- Implementação do sistema de salvamento local utilizando **SwiftData**
- Testes com **CloudKit** para sincronização em nuvem (funcionalidade não incluída na versão de produção)
- Desenvolvimento do sistema de **Data Transfer Objects (DTO)** para transferência segura de dados usando Sendables

**Interface e Experiência do Usuário:**
- Desenvolvimento das interfaces do aplicativo utilizando **SwiftUI**
- Integração com **TipKit** para fornecer orientação sobre recursos durante o uso do app

**Sistema de Mapas e Localização:**
- Implementação do sistema de **MapPins** utilizando **MapKit** e **CoreLocation**
- Desenvolvimento da funcionalidade de marcadores no mapa quando grafites são postados em localizações específicas

**Realidade Aumentada:**
- Testes e implementação de funcionalidades do **ARKit**
- Experimentação com **ARWorldMap** para persistência de objetos AR no ambiente físico
- Criação de novas entidades AR usando **ECS (Entity Component System)**

**Arquitetura:**
- Estruturação da arquitetura do projeto seguindo o padrão **MVVM**

### Processo e Metodologia

**Ideação e Pesquisa:**
- Participação ativa na **ideação do projeto** desde o conceito inicial
- Participação na **indentificação do problema**
- Colaboração no desenvolvimento da proposta de solução e definição de funcionalidades

**Controle de Versão:**
- Utilização de **Conventional Commits** para histórico de versão claro e organizado

---

## Tecnologias Utilizadas

- **SwiftUI** - Framework para desenvolvimento da interface do usuário
- **RealityKit & ARKit** - Gerenciamento de Realidade Aumentada, incluindo postagem, translação, rotação de objetos e criação de entidades
- **MapKit & CoreLocation** - Exibição de mapas e gerenciamento de localização geográfica com marcadores
- **SwiftData & DTO** - Salvamento local de grafites e Data Transfer Objects para transferência segura de dados usando Sendables
- **UIKit** - Inicialização de ARView em UIViewRepresentables
- **TipKit** - Melhorar experiência do usuário com orientações contextuais
- **CloudKit** (Testes) - Testes de compartilhamento de ARWorldMap baseado em nuvem

---

## Autores

**Desenvolvimento:**
- [Jaide Fernando de Carvalho Zardin](https://github.com/JaideZrdn)
- [Pedro Larry](https://github.com/larry4us)

**Design:**
- [Isadora Cristina](https://www.linkedin.com/in/isadora-cristina-farias-bastos-9a992b219/)

---

