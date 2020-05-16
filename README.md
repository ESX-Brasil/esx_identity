# esx_identity

## Requisitos
* Dependências para funcionalidade total
  * [esx_skin](https://github.com/ESX-Brasil/esx_skin)
  * [esx_policejob](https://github.com/ESX-Brasil/esx_policejob)
  * [esx_society](https://github.com/ESX-Brasil/esx_society)

## Download e Instalação

### Usando [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx esx-brasil/esx_identity
```

### Usando Git
```
cd resources
git clone https://github.com/ESX-Brasil/esx_identity [esx]/esx_identity
```

### Manualmente
- Download https://github.com/ESX-Brasil/esx_identity/archive/master.zip
- Coloque no diretório `[esx]`

## Instalação
- Importe `esx_identity.sql` no seu banco de dados
- Adicione isso ao seu `server.cfg`:

```
start esx_identity
```

- Se você estiver usando esx_policejob ou esx_society, precisará ativar o seguinte nos scripts' `config.lua`:
```Config.EnableESXIdentity          = true```

### Comandos
```
/char
/chardel
```

# Legal
### License
esx_identity - rp characters

Copyright (C) 2015-2020 ESXBrasil

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
