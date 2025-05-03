# Restaurantes - Orientado a Objetos

Projeto feito durante o curso da Alura para praticar conceitos de Programação Orientada a Objetos com Python.

## Sobre

Este sistema permite:
- Criar restaurantes com nome e categoria
- Alternar o estado (ativo ou inativo)
- Listar os restaurantes com status visual

Tudo é feito via terminal, com o uso de classes, atributos privados, propriedades e métodos de classe.

## Exemplo de uso

```python
restaurante_praca = Restaurante('praça', 'Gourmet')
restaurante_praca.alternar_estado()
restaurante_pizza = Restaurante('pizza express', 'Italiana')

Restaurante.listar_restaurantes()
