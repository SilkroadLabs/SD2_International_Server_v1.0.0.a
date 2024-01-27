# This branch is precompiled for instant Server Test.
Based on TMProject

## Objective

    Make this project run using the WYD Global/KR Client Version 7.69+ file base

What was accomplished

    Changed the Structures to read the files correctly
    Changed the way in which the client reads the sn.bin file, making it necessary to use the notepad to edit it.
    An itemlist conversion tool has been added
    The base client has been added for its operation
    Lang.txt reading has been added
    Added initialization of @SkyDrive real arena components
    New slots 16 and 17 have been added, the MAX_EQUIP must be changed on the server to 18
    Added some decompilations in the Descompilations folder
    Visual studio 2022 must be used

This project is based on a decompilation of the With Your Destiny game client.
We do not re-divide any copyright in the project. This project was created for study purposes only, with all rights reserved exclusively and entirely to Hanbitsoft.

This code is a faithful decompilation of the original, that is, the code contained here does not refer to what we, developers, would do. As the project as a whole has already been completely finished, having all the necessary functions for the game to be playable, it can be changed as you wish.

## Compilation
The project can only be compiled for Windows using Visual Studio (the project is prepared for the 2019 version, but there is no limitation on the minimum or maximum version).

Compilation for x64 is possible, just use the DirectX x64 dependency to correct problems regarding compilation for this architecture.

## Dependencies
###Visual Studio
To compile the project you will need to have Visual Studio 2022 with the following components installed:

    Desktop development with C++
    C++ ATL for the version of the toolchain being used

The project's only external dependency is DirectX, but it is included in the repository and properly configured.
##Objetivos

    Fazer com que este projeto rode utilizando a base de arquivos do Client WYD Global/KR de Versão 7.69+

O que foi realizado

    Alterado as Estruturas para ler os arquivos de forma correta
    Alterado a forma em que o cliente le o arquivo sn.bin, sendo nescessário utilizar o bloco de notas para editar o mesmo.
    Foi adicionado uma tool de conversão da itemlist
    Foi adicionado o cliente base para o funcionamento do mesmo
    Foi adicionado a leitura do Lang.txt
    Foi adicionado inicialização dos componentes da arena real @SkyDrive
    Foi adicionado os slots novos 16 e 17, deve ser alterado no servidor o MAX_EQUIP para 18
    Foi adicionado algumas descompilações na pasta Descompilations
    Deve se utilizar o visual studio 2022

Este projeto é baseado em uma descompilação do cliente do jogo With Your Destiny. 
Nós não reindividicamos nenhum direito autoral do projeto. Este projeto foi criado apenas para fins de estudo sendo todos os direitos reservados exclusivamente e inteiramente a Hanbitsoft.

Este código é uma descompilação fiel ao original, isto é, o código que aqui consta não remete ao que nós, desenvolvedores, faríamos. Como o projeto como um todo já foi completamente finalizado, tendo todas as funções necessárias para que o jogo seja jogável, o mesmo pode ser alterado como quiser.

## Compilação
O projeto pode ser compilado apenas para Windows utilizando Visual Studio (o projeto está preparado para a versão 2019, mas o mesmo não há limitação quanto a versão mínima ou máxima). 

A compilação para x64 é possível, basta que seja utilizado a dependência para x64 do DirectX assim como corrigir problemas quanto a compilação para esta arquitetura.

## Dependências
###Visual Studio
Para compilar o projeto você precisará ter o Visual Studio 2022 com os seguintes componentes instalados:

    Desenvolvimento para desktop com C++
    ATL do C++ para a versão da toolchain que está sendo utilizada

A única dependência externa do projeto é o DirectX porém o mesmo está incluida no repositório e devidamente configurada.

## Contribuidores TMProject
Este projeto foi desenvolvido por:
- Eric Santos (SKEWED)
- Wed Souza (FREEDOM)
- Kevin Kouketsu (shepher)

# General Public License:

The code is under the [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html), so you can be feel free to study and contribute.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.