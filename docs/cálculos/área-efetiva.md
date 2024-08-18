{{ latex_commands.b }}


{{ latex_commands.lambda_p }}

{{ latex_commands.b_ef }}

# Cálculo - Área efetiva
## Variáveis
{{ glossario.B }}
{{ glossario.b_ef }}
{{ glossario.E }}
{{ glossario.F }}
{{ glossario.k_al }}
{{ glossario.t }}
{{ glossario.sigma }}
{{ glossario.lambda_p }}

>[!info]Valores conhecidos
>$B1$ = {{ valores.B1_mm }} mm -> {{ valores.B1_cm }} cm
>$B2$ = {{ valores.B2_mm }} mm -> {{ valores.B2_cm }} cm
>$B3$ = {{ valores.B3_mm }} mm -> {{ valores.B3_cm }} cm
>$B4$ = {{ valores.B4_mm }} mm -> {{ valores.B4_cm }} cm
>$B5$ = {{ valores.B5_mm }} mm -> {{ valores.B5_cm }} cm
>$E$ = {{ valores.E }}
>[$F$ = {{ valores.F }}](força.md)
>$t$ = {{ valores.t }}

>[!question]Valores calculados
>$b_1$ = {{ valores.b1 }}
>$b_2$ = {{ valores.b2 }}
>$b_3$ = {{ valores.b3 }}
>$b_4$ = {{ valores.b4 }}
>$b_5$ = {{ valores.b5 }}
>$k_{al}$ = {{ valores.k_al }}
>$k_{aa}$ = {{ valores.k_aa }}
>$\lambda_{p1}$ = {{ valores.b1 }}
>$\lambda_{p2}$ = {{ valores.b2 }}
>$\lambda_{p3}$ = {{ valores.b3 }}
>$\lambda_{p4}$ = {{ valores.b4 }}
>$\lambda_{p5}$ = {{ valores.b5 }}
>$b_{ef1}$ = $b_1$ = {{ valores.b1 }}
>$b_{ef2}$ = $b_2$ = {{ valores.b2 }}
>$b_{ef3}$ = $b_3$ = {{ valores.b3 }}
>$b_{ef4}$ = $b_4$ = {{ valores.b4 }}
>$b_{ef5}$ = $b_5$ = {{ valores.b5 }} 

{{ imagens.CT_P_COLUNA_084_1878_Corte_B_B }}

## Calculos do elemento B1
### Comprimento da parte reta ($b_1$)
A largura, b, é o comprimento da parte reta do elemento, descontados os trechos curvos:


{{  formulas.b }}

$$b_1 = {{ valores.B1_cm }} - 2 * {{valores.t  }}$$

$$b_1 = {{  valores.b1  }}$$

### Coeficiete de flambagem local ($k_{al1}$)
{{ imagens.Coeficiente_de_flambagem_local_para_elementos_AL_Caso_a }}

### Largura efetiva ($b_{ef1}$)
{{ formulas.lambda_p_al }}

$$\lambdaP{ {{ valores.b1 }} }{ {{ valores.t }} }{ {{ valores.k_al }} }{ {{ valores.E }} }{ {{ valores.sigma }} }$$

$$\lambda_p={{ valores.lambda_p1 }} < 0,673$$

Como o valor de $\lambda_p$ é menor que 0,673 a largura efetiva será considerada igual ao comprimento da parte reta.

$$\lambda_p = b$$

$$\lambda_p = {{ valores.b1 }} $$

## Calculos do elemento B2
### Comprimento da parte reta ($b_2$)
A largura, b, é o comprimento da parte reta do elemento, descontados os trechos curvos:


{{  formulas.b }}

$$b_2 = {{ valores.B2_cm }} - 2 * {{valores.t  }}$$

$$b_2 = {{  valores.b2  }}$$

### Coeficiete de flambagem local ($k_{aa2}$)
{{ imagens.Coeficiente_de_flambagem_local_para_elementos_AA_Caso_a }}

### Largura efetiva ($b_{ef2}$)
{{ formulas.lambda_p_aa }}

$$\lambdaP{ {{ valores.b2 }} }{ {{ valores.t }} }{ {{ valores.k_aa }} }{ {{ valores.E }} }{ {{ valores.sigma }} }$$

$$\lambda_p={{ valores.lambda_p2 }} < 0,673$$

Como o valor de $\lambda_p$ é menor que 0,673 a largura efetiva será considerada igual ao comprimento da parte reta.

$$\lambda_p = b$$

$$\lambda_p = {{ valores.b2 }} $$


## Calculos do elemento B3
### Comprimento da parte reta ($b_3$)
A largura, b, é o comprimento da parte reta do elemento, descontados os trechos curvos:


{{  formulas.b }}

$$b_2 = {{ valores.B3_cm }} - 2 * {{valores.t  }}$$

$$b_2 = {{  valores.b3  }}$$

### Coeficiete de flambagem local ($k_{aa3}$)
{{ imagens.Coeficiente_de_flambagem_local_para_elementos_AA_Caso_a }}

### Largura efetiva ($b_{ef3}$)
{{ formulas.lambda_p_aa }}

$$\lambdaP{ {{ valores.b3 }} }{ {{ valores.t }} }{ {{ valores.k_aa }} }{ {{ valores.E }} }{ {{ valores.sigma }} }$$

$$\lambda_p={{ valores.lambda_p3 }} < 0,673$$

Como o valor de $\lambda_p$ é menor que 0,673 a largura efetiva será considerada igual ao comprimento da parte reta.

$$\lambda_p = b$$

$$\lambda_p = {{ valores.b3 }} $$

## Calculos do elemento B4
### Comprimento da parte reta ($b_4$)
A largura, b, é o comprimento da parte reta do elemento, descontados os trechos curvos:


{{  formulas.b }}

$$b_4 = {{ valores.B4_cm }} - 2 * {{valores.t  }}$$

$$b_4 = {{  valores.b4  }}$$

### Coeficiete de flambagem local ($k_{aa4}$)
{{ imagens.Coeficiente_de_flambagem_local_para_elementos_AA_Caso_a }}

### Largura efetiva ($b_{ef4}$)
{{ formulas.lambda_p_aa }}

$$\lambdaP{ {{ valores.b4 }} }{ {{ valores.t }} }{ {{ valores.k_aa }} }{ {{ valores.E }} }{ {{ valores.sigma }} }$$

$$\lambda_p={{ valores.lambda_p4 }} < 0,673$$

Como o valor de $\lambda_p$ é menor que 0,673 a largura efetiva será considerada igual ao comprimento da parte reta.

$$\lambda_p = b$$

$$\lambda_p = {{ valores.b4 }} $$

## Calculos do elemento B5
### Comprimento da parte reta ($b_5$)
A largura, b, é o comprimento da parte reta do elemento, descontados os trechos curvos:


{{  formulas.b }}

$$b_5 = {{ valores.B5_cm }} - 2 * {{valores.t  }}$$

$$b_5 = {{  valores.b5  }}$$

### Coeficiete de flambagem local ($k_{al5}$)
{{ imagens.Coeficiente_de_flambagem_local_para_elementos_AA_Caso_a }}

### Largura efetiva ($b_{ef5}$)
{{ formulas.lambda_p_aa }}

$$\lambdaP{ {{ valores.b5 }} }{ {{ valores.t }} }{ {{ valores.k_aa }} }{ {{ valores.E }} }{ {{ valores.sigma }} }$$

$$\lambda_p={{ valores.lambda_p5 }} < 0,673$$

Como o valor de $\lambda_p$ é menor que 0,673 a largura efetiva será considerada igual ao comprimento da parte reta.

$$\lambda_p = b$$

$$\lambda_p = {{ valores.b5 }} $$