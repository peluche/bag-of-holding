# Bag of Holding (aka. Quantization)

## results
| Model                | Accuracy | Size (bytes) |
|----------------------|----------|--------------|
| Base fp32            | 0.9468   | 560424       |
| Quantized int8       | 0.9464   | 140712       |

## formulas
![symmetric-quantization.png](imgs/symmetric-quantization.png)
![symmetric-matmul.png](imgs/symmetric-matmul.png)
![asymmetric-quantization.png](imgs/asymmetric-quantization.png)
![asymmetric-matmul.png](imgs/asymmetric-matmul.png)
