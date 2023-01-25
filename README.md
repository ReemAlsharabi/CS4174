## Types of cyber attacks against ML models
https://www.linode.com/docs/guides/machine-learning-cyber-attacks/#evasion

# Suggested Topics:

## Investigating the impact of DDoS attacks on the performance of deep learning models used for security purposes such as intrusion detection or malware detection.
This project could involve simulating DDoS attacks on a deep learning model, measuring its performance before and after the attack, and identifying any vulnerabilities or weaknesses that the attack exposes. The project could also include the development of a defense mechanism to protect the deep learning model against DDoS attacks.

_An example of how a DDoS attack can cause a deep learning model to fail is by overwhelming the model with a large amount of traffic that is similar to the traffic that the model is trained to detect, this can cause the model to label malicious traffic as benign, allowing the attacker to bypass the model's security measures._

Adversarial attacks involve introducing small, carefully crafted perturbations to input data (such as images) that cause a machine learning model to misclassify it. In the case of a DDoS attack, an attacker could use this technique to create malicious images that are misclassified as a specific target (such as a login page or important website) by the machine learning model used to classify traffic. The attacker could then send these malicious images in large quantities to the targeted website, causing the model to incorrectly redirect traffic to the attacker's desired location. This could potentially overload the targeted website with traffic, causing a denial of service.

**Traffic, such as that generated during a DDoS attack, can cause an adversarial attack or a deep learning model to fail in several ways**
- Overload: A DDoS attack can overload a server or network with a large amount of traffic, which can cause the system to crash or become unstable. This can make it easier for an attacker to exploit vulnerabilities in the system, such as those that may exist in a deep learning model.
- Distortion of input data: A DDoS attack can also cause distortion of input data that is being used to train or test a deep learning model. This can cause the model to produce incorrect or unreliable results.
- Poisoning: A DDoS attack can also be used as a form of data poisoning, where the attacker sends a large amount of malicious traffic to a deep learning model, in an attempt to cause it to misclassify or make mistakes.


## Exploring the Vulnerabilities of Autonomous Cars to Adversarial Attacks and Developing Robust Defense Strategies
This topic will investigate the potential vulnerabilities of autonomous cars to adversarial attacks, such as targeted misclassification of objects, and evaluate the effectiveness of various defense techniques, such as adversarial training and input preprocessing.
The project will aim to develop robust defense strategies to protect autonomous cars from such attacks and improve their safety and reliability.

Some potential defense strategies that can be explored in the context of autonomous cars and adversarial attacks include:
- Anomaly detection: This involves identifying abnormal behavior in the input data and flagging it as potentially adversarial. This can be done using techniques such as statistical analysis or machine learning.
- Adversarial training: This involves creating a dataset of adversarial examples and using them to train the model, making it more robust to similar attacks in the future.
- Adversarial training with Generative models: Using generative models to generate adversarial examples and use them for adversarial training.
- Regularization methods: Using regularization techniques such as weight decay and dropout to make the model more robust to adversarial examples.
- Input preprocessing: This includes techniques such as image resizing, cropping, and color space transformations to preprocess the input images before they are fed into the model. This can make it more difficult for an attacker to craft adversarial examples that will be successful.
- Input transformation: This includes techniques such as randomization of input before feeding to the model, this could make it difficult for an attacker to craft adversarial examples that will be successful.
- Ensemble methods: This involves using multiple models and combining their predictions to make a final decision. This can make it more difficult for an attacker to fool all of the models at once.
- Defending against physical attacks: This includes techniques such as using sensor fusion and adding physical barriers to protect the sensors of the autonomous car from being tampered with.

**cyber security techniques to protect autonomous cars from adversarial attacks:**

- Malware protection: Ensuring that the software and systems running on the autonomous car are free from malware, which could be used by an attacker to take control of the car.
- Denial of Service (DoS) protection: Implementing measures to prevent DoS attacks on the autonomous car's communication systems, which could be used to disrupt the operation of the car.
- Cryptography: Using encryption to protect the communication between the autonomous car and other systems, such as the car's control center or other cars on the road.
- Network security: Securing the communication networks used by the autonomous car to prevent unauthorized access or eavesdropping by attackers.
- Secure boot and firmware protection: Ensuring that the firmware, operating system and any other software running on the autonomous car is authentic and has not been tampered with by an attacker.
- Intrusion detection and prevention: Implementing systems to detect and prevent unauthorized access to the autonomous car's systems.
- Monitoring and logging: Keeping track of the activity on the autonomous car's systems, so that any suspicious activity can be detected and investigated.
- Incident response and management: Having a plan in place to respond to security incidents and manage the aftermath.

**Further details on ways to implement measures to prevent Denial of Service (DoS) attacks on the autonomous car's communication systems:**
- Network segmentation: This involves dividing the communication network of the autonomous car into smaller segments, and limiting the communication between these segments. This makes it more difficult for an attacker to launch a DoS attack that affects the entire network.
- Firewall: Implementing a firewall to prevent unauthorized access to the car's communication systems and block malicious traffic.
- Traffic shaping: Using techniques such as rate limiting, traffic prioritization, and congestion control to manage the flow of traffic on the car's communication systems, making it more difficult for an attacker to launch a DoS attack.
- Distributed denial of service (DDoS) protection: DDoS protection services can be used to detect and mitigate DDoS attacks by filtering and blocking malicious traffic.
- Intrusion detection and prevention systems: Intrusion detection and prevention systems (IDPS) can be used to detect and prevent DoS attacks, by analyzing network traffic and identifying patterns indicative of an attack.
- Monitoring and logging: Keeping track of the activity on the car's communication systems, so that any suspicious activity can be detected and investigated.
- Incident response and management: Having a plan in place to respond to security incidents and manage the aftermath, including DoS attacks.
- Network redundancy: Having multiple network paths and failover mechanisms in place to minimize the impact of a DoS attack on the car's communication systems.

_Keep in mind that DoS attacks can take many forms and can target different parts of the system, so it is important to conduct a thorough risk assessment to identify potential attack vectors and implement appropriate countermeasures._

## Also,

Developing robust defense strategies against cyber attacks in autonomous cars is a critical area of research, as the safety of passengers and other road users may be at risk if an attack is successful. Autonomous cars rely heavily on the performance of their deep learning models for tasks such as object detection, navigation, and control, making them vulnerable to both DDoS attacks and adversarial attacks.

One approach to developing defense strategies is to use techniques such as intrusion detection systems, firewalls, and secure communication protocols to prevent unauthorized access to the car's systems. Additionally, techniques such as load balancing and traffic shaping can be used to distribute traffic and minimize the impact of a DDoS attack.

Another approach is to use techniques such as adversarial training and defensive distillation to make the deep learning models used in autonomous cars more robust to adversarial attacks. This involves training the models on a dataset that includes adversarial examples, so that the models can learn to recognize and defend against these types of inputs.

It is also important to have a good monitoring and logging system to detect an attack as soon as possible, and to have a well-defined incident response plan that can be activated in the event of an attack.

Overall, the development of robust defense strategies against cyber attacks in autonomous cars requires a multi-disciplinary approach that combines expertise in deep learning, computer vision, and cybersecurity to ensure the safety and security of the autonomous cars and their passengers.

## Investigating the impact of cyber attacks on the performance of deep learning models in drones
As drones rely heavily on the performance of their deep learning models for tasks such as object detection, navigation, and control. Cyber attacks on drones can cause disruptions in communication between the drone and its control systems, leading to a loss of control or navigation errors. Additionally, cyber attacks can also cause delays in processing the data needed for the deep learning models to make decisions, leading to a decrease in performance, and in some cases, could cause the drone to crash.

To investigate the impact of cyber attacks on the performance of deep learning models in drones, researchers may conduct experiments in which they simulate different types of cyber attacks on a drone's communication systems and observe the effects on the drone's performance. This can include studying the effects of DDoS attacks, which aim to overload a network or server by flooding it with a large amount of traffic, and adversarial attacks, which aim to fool a deep learning model by providing it with inputs that are specifically designed to cause the model to make incorrect predictions.

Researchers may also analyze real-world data from drones that have been impacted by cyber attacks to understand the effects in practice. This can provide valuable insights into the types of attacks that drones are most vulnerable to and the strategies that can be used to defend against them.

Additionally, researchers are also focusing on the development of robust and secure communication systems for drones that can resist cyber attacks and ensure the continuity of the drone's operation during an attack. This includes the use of secure communication protocols, intrusion detection systems, and firewalls to prevent unauthorized access to the drone's systems.

## Papers:

* Hardening machine learning denial of service (DoS) defences against adversarial attacks in IoT smart home networks

https://reader.elsevier.com/reader/sd/pii/S0167404821001760?token=CFB193CAA8011D6160A1A3FBA663D2316B69BAB71B16DC5D8605D15BD359536A1A3D97989C0B51E58D82ED06CAC7516E&originRegion=eu-west-1&originCreation=20230125164309

* Security Issues and Defensive Approaches in Deep Learning Frameworks

https://www.sciopen.com/article_pdf/1496413761240186882.pdf

* Adversarial Attacks and Defenses in Deep Learning

https://reader.elsevier.com/reader/sd/pii/S209580991930503X?token=0A1017A77541A0BD8F40E571C6FDBA5C337C3F608C4C973AD855BCB8F67864A4CF0918A9C023319F34A6154465A7F526&originRegion=eu-west-1&originCreation=20230125213915

* Exploring Security Vulnerabilities of Deep Learning Models by Adversarial Attacks (word replacement method)

https://downloads.hindawi.com/journals/wcmc/2021/9969867.pdf

* Memory-Augmented Insider Threat Detection with Temporal-Spatial Fusion (user behaviors)

https://downloads.hindawi.com/journals/scn/2022/6418420.pdf
