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

1	Common Chrysanthemum	- Chrysanthemum morifolium	- Bright ornamental flowers used in gardens and arrangements

2	Common Yarrow -	Achillea millefolium -	Hardy herb with feathery leaves and medicinal uses

3	Sunflower -	Helianthus annuus	- Tall plant with large yellow flowers that follow the sun

4	Garden Tulip -	Tulipa gesneriana -	Cup-shaped ornamental flower

5	Lilac -	Syringa vulgaris -	Fragrant flowering shrub

6	Spearmint	- Mentha spicata -	Aromatic herb used in cooking and tea

7	Rosemary -	Salvia rosmarinus -	Woody herb used as a culinary spice

8	Thyme -	Thymus vulgaris -	Small aromatic herb

9	German Chamomile - Matricaria chamomilla	- Medicinal plant used in calming teas

10	Sweet Basil	- Ocimum basilicum -	Popular culinary herb

11	Holy Basil (Tulsi) -	Ocimum tenuiflorum	- Medicinal and religious plant

12	Petunia -	Petunia × atkinsiana	- Colorful ornamental plant

13	Pot Marigold -	Calendula officinalis -	Bright flowers used in remedies

14	Rose-Scented Geranium -	Pelargonium graveolens -	Fragrant plant used in perfumes

15	Sage	- Salvia officinalis - 	Culinary and medicinal herb

16	Golden Shower Tree	- Cassia fistula -	Tree with long yellow flower clusters

17	Stevia -	Stevia rebaudiana -	Natural sweetener plant

18	Ivy Geranium -	Pelargonium peltatum	- Trailing ornamental plant

19	Carnation -	Dianthus caryophyllus -	Fragrant flower with ruffled petals

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

