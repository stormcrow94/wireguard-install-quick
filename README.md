# Instalador do WireGuard

**Este projeto é um script em bash que tem como objetivo configurar o WireGuard em um servidor Linux da maneira mais simples possível!**

WireGuard é uma VPN ponto a ponto que pode ser usada de diversas formas. Aqui, o cliente encaminha todo o tráfego por um túnel criptografado até o servidor. O servidor aplica NAT no tráfego do cliente para que pareça que o cliente está navegando com o IP do servidor.

O script oferece suporte tanto para IPv4 quanto para IPv6.

## Requisitos

Distribuições suportadas:

- AlmaLinux >= 8
- Arch Linux
- CentOS Stream >= 8
- Debian >= 10
- Fedora >= 32
- Oracle Linux
- Rocky Linux >= 8
- Ubuntu >= 18.04

## Uso

Baixe o script e execute-o. Responda às perguntas exibidas e ele fará o restante.

```bash
chmod +x wireguard-install.sh
./wireguard-install.sh
```

O script instalará o WireGuard (módulo de kernel e ferramentas) no servidor, configurará o serviço e criará um arquivo de configuração para o cliente.

Execute o script novamente para adicionar ou remover clientes!

## Contribuindo

### Formatação de código

Utilizamos shellcheck e shfmt para garantir boas práticas de bash. Eles são executados para cada commit ou pull request pelo GitHub Actions.

## Créditos e Licença

Este projeto está sob a licença MIT.
