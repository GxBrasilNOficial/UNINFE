# Genexus UNINFE


## Instalação
Importar o arquivo _.xpz_ na KB.
    Menu Knowledge Manager -> Import -> selecionar o arquivo _.xpz_

![image](https://user-images.githubusercontent.com/1467860/166702430-5570b17a-c5f7-497b-9862-24bc2bed1e4d.png)

## Exemplo de uso
![image](https://user-images.githubusercontent.com/1467860/166702126-969dccc9-ed41-4f66-9bb7-5f63a9b05db5.png)

```Gx
Código Gx aqui...

    &udtbInterfaceUnimakeDLL.NomeArquivoCertificado	    = &NomeArquivoCertificado
	&udtbInterfaceUnimakeDLL.SenhaArquivoCertificado	= &SenhaArquivoCertificado

	&udtbInterfaceUnimakeDLL.CarregaCertificado()

    &Retorno = &udtbInterfaceUnimakeDLL.DadosDoCertificado()

## Iniciado por:
Antonio – [@antoniojosedev](https://github.com/antoniojosedev)
