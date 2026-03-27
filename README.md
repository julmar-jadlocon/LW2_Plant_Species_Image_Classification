**🌿 Non-Native Cultivated Plant Classifier**
📌 Project Overview

This project focuses on developing an image classification model using Teachable Machine to identify different non-native cultivated plant species.

**🎯 Objectives**
The main goals of this project are to:

🌱 Automatically identify and classify 20 non-native cultivated plants
📚 Assist students and users in recognizing plant species through images
🤖 Demonstrate the application of machine learning in plant classification
🧪 Provide a simple and accessible tool for education and research
🧠 Model Information
Platform Used: Teachable Machine
Model Type: Image Classification
Input: Plant images
Output: Predicted plant species
🌼 Plant Classes

The model is trained to recognize the following 20 plant species:

**#	Common Name	Scientific Name	Description**

<img src="https://github.com/user-attachments/assets/5090e364-ccf6-4373-a2bc-840a8b208664" width="250">
1	Common Chrysanthemum	- Chrysanthemum morifolium	- Bright ornamental flowers used in gardens and arrangements

![large (36)](https://github.com/user-attachments/assets/baabc897-2b2a-4237-bf33-65a3f4e3afaf)
2	Common Yarrow -	Achillea millefolium -	Hardy herb with feathery leaves and medicinal uses

![large - 2026-03-04T103500 143](https://github.com/user-attachments/assets/52673c7f-919f-43c8-afad-80de041a0367)
3	Sunflower -	Helianthus annuus	- Tall plant with large yellow flowers that follow the sun

![large - 2026-03-09T134821 567](https://github.com/user-attachments/assets/f4b13944-a542-407d-a412-3996b9e573a7)
4	Garden Tulip -	Tulipa gesneriana -	Cup-shaped ornamental flower

![large (2)](https://github.com/user-attachments/assets/bbdb1164-5d6a-4ad7-92a5-c713a230d2c4)
5	Lilac -	Syringa vulgaris -	Fragrant flowering shrub

![large - 2026-03-09T152757 553](https://github.com/user-attachments/assets/82c5f6a1-c361-4d77-a479-abf439cfa520)
6	Spearmint	- Mentha spicata -	Aromatic herb used in cooking and tea

![large (10)](https://github.com/user-attachments/assets/112b4108-c5c1-4ddb-b9ae-1e0f642cd299)
7	Rosemary -	Salvia rosmarinus -	Woody herb used as a culinary spice

![large (60)](https://github.com/user-attachments/assets/84253e10-fcaf-440a-a1a2-ae5e3da2797e)
8	Thyme -	Thymus vulgaris -	Small aromatic herb

![00005_bigcommerce_82b601d11eb1](https://github.com/user-attachments/assets/6c65b9f7-b6b3-4be0-9711-dd91d7f8821b)
9	German Chamomile - Matricaria chamomilla	- Medicinal plant used in calming teas

![large (36)](https://github.com/user-attachments/assets/16223771-9fce-42e9-b261-db92d24469dd)
10	Sweet Basil	- Ocimum basilicum -	Popular culinary herb

![large (11)](https://github.com/user-attachments/assets/ea5dca02-50e2-4834-990d-fb536403f453)
11	Holy Basil (Tulsi) -	Ocimum tenuiflorum	- Medicinal and religious plant

![00003_plantworldse_72de616406b7](https://github.com/user-attachments/assets/189b50a1-2142-4906-a1b3-2366a0467b8c)
12	Petunia -	Petunia × atkinsiana	- Colorful ornamental plant

![large (2)](https://github.com/user-attachments/assets/b06620be-ef8a-4454-8ba3-97790cd70242)
13	Pot Marigold -	Calendula officinalis -	Bright flowers used in remedies

![large](https://github.com/user-attachments/assets/71831bc3-6f03-41f3-bc4d-04d659b384e0)
14	Scented Geranium -	Pelargonium graveolens -	Fragrant plant used in perfumes

![large (3)](https://github.com/user-attachments/assets/c0641dca-d048-4a69-aadf-87a44f873c60)
15	Sage	- Salvia officinalis - 	Culinary and medicinal herb

![large (48)](https://github.com/user-attachments/assets/1fc9dd7c-3cf4-43ed-a21e-90be60177e57)
16	Golden Shower Tree	- Cassia fistula -	Tree with long yellow flower clusters

![large (6)](https://github.com/user-attachments/assets/bdf8621b-11d8-4107-9ab7-1f9c4378b45c)
17	Stevia -	Stevia rebaudiana -	Natural sweetener plant

![large (8)](https://github.com/user-attachments/assets/452f6a7b-415d-4f87-8141-fdf499a5ff7f)
18	Ivy Geranium -	Pelargonium peltatum	- Trailing ornamental plant

![large (30)](https://github.com/user-attachments/assets/a3a4f11e-2419-4c6c-bb9e-ef481cf8516f)
19	Carnation -	Dianthus caryophyllus -	Fragrant flower with ruffled petals

![large (1)](https://github.com/user-attachments/assets/ff530190-b436-4e8e-98cb-ca059aa9e7a5)
20	Busy Lizzie -	Impatiens walleriana -	Shade-loving plant with vibrant blooms


🏋️ Model Training Details
The model was trained using the following parameters:

<img width="209" height="322" alt="Screenshot 2026-03-27 193046" src="https://github.com/user-attachments/assets/5446bb7d-e640-4663-9a56-c2b5e1658c66" />

Epochs: 23

Batch Size: 16

Learning Rate: 0.0001

Number of Images per Class: 250

These parameters were chosen to balance training time and model accuracy while ensuring good generalization across plant species. 


📊 Model Evaluation
The model’s performance was evaluated using the following metrics:

📌 Confusion Matrix – Shows how well the model distinguishes between different plant classes

<img width="176" height="344" alt="Screenshot 2026-03-27 131958" src="https://github.com/user-attachments/assets/b6932ef6-2be2-4f88-a954-62cbb183a30c" />

<img width="173" height="346" alt="Screenshot 2026-03-27 132030" src="https://github.com/user-attachments/assets/d63ee5e6-4866-41cd-9d2a-41cd5a19213c" />

📌 Accuracy per Class – Measures performance for each individual plant species

<img width="181" height="400" alt="Screenshot 2026-03-27 132056" src="https://github.com/user-attachments/assets/8e107542-bb4d-4d8d-b3b7-0d830166c71a" />

📌 Overall Model Accuracy – Indicates the general prediction accuracy of the model

<img width="184" height="323" alt="Screenshot 2026-03-27 131929" src="https://github.com/user-attachments/assets/409551e8-fac0-4f21-97d5-de1f3c6cfee0" />

