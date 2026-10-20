# Term Frequency

Mede a frequência com que um termo aparece em seu próprio documento. O contexto é o próprio documento analisado (**Específico**).

## Glossário:

| Variável | Significado |
| :-: | :- |
| **T** | Token analisado. |
| **D** | Documento que contém o token analisado. |

## Cálculo:

**TF** = $\frac{\text{Quantidade de vezes que } T \text{ aparece em } D}{\text{Quantidade de tokens de } D}$

# Inverse Document Frequency

Mede a frequência com que um termo aparece em todo o corpus. O contexto é o corpus todo (**Geral**).

## Glossário:

| Variável | Significado |
| :-: | :- |
| **N** | Número total de documentos do corpus. |
| **T** | Documentos do corpus que contém o token analisado. |

## Cálculo:

**IDF** = log($\frac{\text{Número de documentos presentes no corpus}}{\text{Documentos contendo } T}$)

**Smooth IDF** = log($\frac{\text{Número de documentos presentes no corpus + 1}}{\text{Documentos contendo } T \text{ + 1}}$) + 1

# Resultado Final

**TF-IDF** = TF X IDF

**Observação**: Tenha em mente que **"TF-IDF"** é uma nomenclatura, e não uma operação de subtração.