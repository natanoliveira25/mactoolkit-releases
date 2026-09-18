# MacToolkit — pacotes de atualização

Este repositório existe só para hospedar os pacotes que o app baixa ao se
atualizar. O código-fonte fica em um repositório privado.

O app consulta sempre o mesmo endereço:

    https://github.com/natanoliveira25/mactoolkit-releases/releases/latest/download/mactoolkit.json

O manifesto traz versão, notas, URL do pacote e o sha256. Antes de instalar, o
app confere o sha256 **e** a assinatura Developer ID do bundle baixado — é isso
que torna seguro distribuir por um endereço público.
