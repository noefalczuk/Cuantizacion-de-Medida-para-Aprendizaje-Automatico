# Cuantización de medida para aprendizaje automático

Resumen

El Aprendizaje Automático (Machine Learning) requiere el manejo eficiente de grandes volúmenes de datos, lo que plantea desafíos computacionales significativos. Una técnica clave para abordar estos desafíos es la cuantización de medidas, cuyo objetivo es reemplazar una medida de probabilidad $\mu$ por una aproximación discreta, con soporte finito y más pequeño, preservando la medida de la manera más fiel posible.

Esta tesis estudia los fundamentos teóricos y las aplicaciones de la cuantización, partiendo de conceptos fundamentales como la distancia de Wasserstein [1,2,3] y la noción de baricentro de Wasserstein [4,5]. Se revisan los principios de la cuantización de una única medida de probabilidad [6,7], incluyendo su estrecha relación con el algoritmo de $k$-means y los métodos clásicos de cuantización [8].

Además, este trabajo introduce y explora un nuevo concepto: la Cuantización Conjunta de Medidas, que extiende el principio de aproximación óptima a una colección de medidas $(\mu_1, \dots, \mu_N)$. El objetivo es encontrar un único cuantizador que minimice simultáneamente la pérdida de información en todas las medidas.

Finalmente, los resultados muestran que la cuantización bajo este enfoque conjunto no solo proporciona aproximaciones eficientes de las medidas individuales, sino que también da lugar a un método efectivo para aproximar el baricentro de Wasserstein de un conjunto de medidas. Esta aproximación cuantizada simplifica significativamente el cálculo del baricentro, ofreciendo una herramienta computacionalmente más tratable para tareas centrales del Aprendizaje Automático que dependen de la agregación óptima de distribuciones de probabilidad [9–13].

Abstract

Machine Learning requires the efficient handling of large volumes of data, which poses significant computational challenges. A key technique to address these challenges is measure quantization, which aims to replace a probability measure $\mu$ with a discrete approximation supported on a finite and smaller set, while preserving the measure as accurately as possible.

This thesis studies the theoretical foundations and applications of quantization, starting from fundamental concepts such as the Wasserstein distance [1,2,3] and the notion of the Wasserstein barycenter [4,5]. We review the principles of quantizing a single probability measure [6,7], including its close connection with the $k$-means algorithm and classical quantization methods [8].

Moreover, this work introduces and explores a new concept: Joint Quantization of Measures, which extends the principle of optimal approximation to a collection of measures $(\mu_1, \dots, \mu_N)$. The goal is to find a single quantizer that simultaneously minimizes the loss of information across all measures.

Finally, the results show that quantization under this joint framework not only provides efficient approximations of individual measures, but also yields an effective method for approximating the Wasserstein barycenter of a set of measures. This quantized approximation significantly simplifies barycenter computation, offering a more tractable computational tool for core Machine Learning tasks that rely on the optimal aggregation of probability distributions [9–13].

References

[1] C. Villani. Optimal Transport: Old and New. Springer, 2009.

[2] V. Panaretos, Y. Zemel. An Invitation to Statistics in Wasserstein Space. Springer, 2020.

[3] N. G. Chehebar. Transporte Óptimo y Baricentro con distancia de Fermat.
Licenciatura Thesis, Universidad de Buenos Aires, 2021.

[4] M. Agueh, G. Carlier. Barycenters in the Wasserstein Space.
SIAM Journal on Mathematical Analysis, 43(2):904–924, 2011.

[5] T. Le Gouic, J.-M. Loubes. Existence and Consistency of Wasserstein Barycenters.
Probability Theory and Related Fields, 168(3–4):901–917, 2017.

[6] S. Graf, H. Luschgy. Foundations of Quantization for Probability Distributions.
Springer, Lecture Notes in Mathematics 1730, 2000.

[7] N. Chéhère. Quantization and Empirical Measures: A Probabilistic Approach.
ESAIM: Probability and Statistics, 24:580–602, 2020.

[8] D. Pollard. Quantization and the Method of $k$-Means.
IEEE Transactions on Information Theory, 1982.

[9] A. Tong et al. Conditional Flow Matching: Simulation-Free Dynamic Optimal Transport.
CoRR abs/2302.00482, 2023.

[10] Y. Lipman et al. Flow Matching for Generative Modeling.
ICLR, 2023.

[11] P. Kairouz et al. Advances and Open Problems in Federated Learning.
arXiv:1912.04977, 2021.

[12] P. Kairouz et al. Federated Learning in Practice: Reflections and Projections.
arXiv:2410.08892, 2024.

[13] Y. Lin et al. Deep Gradient Compression: Reducing the Communication Bandwidth for Distributed Training.
arXiv:1712.01887, 2018.
