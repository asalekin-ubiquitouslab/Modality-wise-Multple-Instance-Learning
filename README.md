# Modality-wise-Multple-Instance-Learning
 This reposistory contains the code for the paper Psychophysiological Arousal in Young Children Who Stutter: An Interpretable AI Approach accepted for IMWUT 2022

## Modality Invariant-MIL (MI-MIL) Approach

the MI-MIL approach takes the modality-specific bag representations (𝐵𝑚 ={𝑥1𝑚,𝑥2𝑚,...𝑥𝑘𝑚}, 𝑘 = 19,𝑚 = EDA, HR, RSP-amp, RSP-rate) of a 20s physiological sensing data as input. As shown in figure below, MI-MIL has four components: (1) modality specific embedding block, (2) modality specific self-attention pooling block, (3) modality fusion Block, and (4) classifier Block. While the first two blocks are applied to each modality 𝑚 independently, the latter two combine the cross-modality information to generate inference.

![MI-MIL](https://github.com/asalekin-ubiquitouslab/Modality-wise-Multple-Instance-Learning/blob/main/MIMIL.png)

### ACM Reference Format:
Harshit Sharma, Yi Xiao, Victoria Tumanova, and Asif Salekin. 2022. Psychophysiological Arousal in Young Children Who Stutter: An Interpretable AI Approach. Proc. ACM Interact. Mob. Wearable Ubiquitous Technol. 6, 3, Article 137 (September 2022), 32 pages. https://doi.org/10.1145/3550326

### Contact
hsharm04@syr.edu
