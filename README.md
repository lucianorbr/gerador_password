<h1 align="center">
Gerador de Senhas aleatórios 
</h1>

<p align="center">Projeto diciplicar.</p>

## Participantes

[Luciano Ribeiro](https://github.com/lucianorbr)

## Tecnologias

- [x] Go

## 🚀 Getting started

```bash
# Clone this repository
$ git clone https://github.com/lucianorbr/gerador_password
# Access the repository
$ cd gerador_password
$ go run main.go

```
## O Projeito
- Vem de uma necedidade de senhas fortes e distintas para diversas ocasiões:
- CLI pode gerar uma grande quantidade de senhas 

## Flags:

      --characters string   Character set for the config
      --exclude-ambiguous   Exclude ambiguous characters (default true)
      --exclude-similar     Exclude similar characters (default true)
      --help                help for go-generate-password
      --length int          Length of the password (default 24)
      --lowercase           Include lowercase letters (default true)
      --numbers             Include numbers (default true)
      --symbols             Include symbols (default true)
      --times int           How many passwords to generate (default 1)
      --uppercase           Include uppercase letters (default true)
      
## For example:

      --go run main.go
      --5PU?rG-w9YkDus4?AbmKd+Z*

##  go run main.go -n 5 --length 16 --symbols=false
      --X89R4HvATgg7HSKk
      --YMwMPnXp7cnMTNdZ
      --RZWKAvyxFxDWRB8u
      --PvKb6uP4N7vAMVsD
      --KHttvhevGrTYptM5
      
## Example using custom character set:

      --go run main.go -n 5 --characters=abcdefg01
      --10cecfcfe0bea1fdcbb1afcf
      --bfcgbgg0dccafdacdaa1de01
      --gb0ggcffcefae0bb1ac0bbge
      --abafbc1bbaff0cfbdgaee11d
      --1fge0fcbccabda0g0a01ffc0
