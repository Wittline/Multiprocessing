# Multiprocessing - Geometric decomposition
Improving the Performance in the Statistical Redistribution of Message Symbols using Architectural patterns for Parallel Programming

<details open>   
<summary> 1. <a href="https://wittline.github.io/Multiprocessing/Multiprocessing/Pages/paper.pdf">Paper </a></summary>   
</details>

<details open>   
<summary> 2. <a href="https://wittline.github.io/Multiprocessing/Pages/Multiprocessing.html">Code </a></summary>               
</details>

<details open>   
<summary> 3. Results </summary>
   
The architectural design pattern for parallel programming called geometric decomposition helped us to reach the results we expected, reducing times by 52.28% for file 1 using 3 cores, and reduce by 28.20% for file 2 using 7 cores, these experiments help us satisfy most of quality attributes and avoid trade-offs that at first glance may seem impossible and at the same time satisfy most of the functional requirements

It is important to highlight that the choice of the K factor is based on the one that offers the best compression, but when we choose a K factor very far from its consecutive one using large files perhaps the parallelism may degrade the performance. Sometimes it is a good decision to add some noise to the original message since this way you can get closer K factors, and this would be another topic of research.

</details>

![alt text](https://wittline.github.io/Multiprocessing/Images/Grafica2.PNG)
![alt text](https://wittline.github.io/Multiprocessing/Images/grafica1.PNG)

## Contributing and Feedback
Any ideas or feedback about this repository?. Help me to improve it.

## Authors
- Created by <a href="https://www.linkedin.com/in/ramsescoraspe"><strong>Ramses Alexander Coraspe Valdez</strong></a>
- Created on 2019

## License
This project is licensed under the terms of the MIT license.

