# Adaptação do template protostar do Joomla 3

O protostart é um template aparentemente simples mas cheio de bons recursos.

Mantive muita coisa, apenas removi as partes que considerei mais complexas ou sem necessidade:
- Removi dois js
- BRemovi ba parte do index.php (removi as fontes do Google)
- Removi boa parte do xml
- Removi o Less
- Removi o img
- Removi o language

## Posições que conservei:

    Título do Site (9)                position-0 (3search à direita)

    position-1 (12menu)

    banner(12)

    position-8 (3vazia)  position-3 (6logo)      position-7 (3)

                        message
                        component (12)

                        position-2 (12breadcrumbs)

    footer(12)

debug(12)

Removi as demais posições, que não aparecem com tp=1.

Usar position-3 para o mod_ribafs_portfolio

8 - left
7 - right

O arquivo component.php do template trabalha a visualização do template.

## Licença

GPL 3
