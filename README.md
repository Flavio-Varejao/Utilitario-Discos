# Utilitario de Discos  

## Utilitário para dispositivos de armazenamento  

Site:  
Autor:      Flávio Varejão  
Manutenção: Flávio Varejão  

## mountdev.sh  

Este script formata e/ou grava uma imagem USB em um dispositivo de armazenamento externo.  

### Permissão  

Dê permissão de execução (primeiro acesso):  
```
    $ chmod +x mountdev.sh  
```

### Execução  

Neste exemplo o script vai formatar o seu dispositivo:  
```
    $ ./mountdev.sh -f  
``` 

O script identifica se o dispositivo está montado, se estiver montado ele abre um menu com as opções. No processo de formatar é possível selecionar entre FAT32, NTFS e EXT4.  

ATENÇÃO!  

Este script identifica o dispositivo de armazenamento montado na porta usb, mas não foi testado em uma máquina com mais de 1 dispositivo de armazenamento usb. Logo, devido a essa limitação, o script está incompleto e precisa ser aperfeiçoado. Verifique o diretório do pendrive ou hd externo. Não me responsabilizo por perdas de dados!  

### Histórico:  

  v1.0 09/06/2020, Flávio:  
  - Adicionado variáveis, comandos de testes, funções e execução.  
  
### Testado em:  

  Bash 5.0.17  
  
