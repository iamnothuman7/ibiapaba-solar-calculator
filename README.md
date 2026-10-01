# Ibiapaba Solar Calculator

Versão do simulador de economia da Associação Ibiapaba Solar em HTML, CSS e JavaScript. O arquivo de entrada desta versão é `deepseek_html_20251125_f7da2f.html`, e não `index.html`.

Para uma versão com entrada convencional e link de demonstração, consulte [ibiapaba-solar](https://github.com/iamnothuman7/ibiapaba-solar). Os dois repositórios permanecem separados para preservar seus históricos.

## Recursos

- Entrada por valor da fatura ou consumo em kWh.
- Comparação entre valores calculados com tarifas fixadas no código.
- Interface adaptável e link de contato com a simulação pelo WhatsApp.

O código implementa a expressão `(Cmc - Cgd) × 0,8` e constantes de tarifa e iluminação. Esses parâmetros não são atualizados por uma API. A demonstração não garante economia real nem substitui a conferência comercial e técnica dos valores.

## Executar localmente

```sh
git clone https://github.com/iamnothuman7/ibiapaba-solar-calculator.git
cd ibiapaba-solar-calculator
python -m http.server 8000 --bind 127.0.0.1
```

Abra `http://127.0.0.1:8000/deepseek_html_20251125_f7da2f.html`. O arquivo `logo.png` deve permanecer ao lado do HTML.

## Validação e uso

Não há testes automatizados. Confira entradas inválidas, parâmetros do cálculo, contato comercial e layout em celular antes de reutilizar. A URL raiz de uma hospedagem estática não deve ser anunciada como demonstração sem configurar uma página de entrada.

Não há licença de redistribuição declarada. Marcas e materiais da associação não são liberados para uso por este README.
