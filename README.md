# Backend_Bachelor

## Projektbeschreibung
Das vorliegende Projekt knüpft an eine zuvor abgeschlossenes Projekt an, in deren Rahmen eine erste prototypische Lernumgebung in der Unreal Engine entwickelt wurde. In dieser Lernumgebung kam das bestehende Large Language Model (LLM) zum Einsatz, um das Verhalten sowie die Dialogfähigkeit von Non-Player-Character (NPC) dynamischer zu gestalten und so eine immersive und interaktive Lernumgebung zu schaffen. 

## Ziel
Um die NPC-Tutoren in der Lernwelt adaptiver und Lernstand sensitiv zu machen, kann das Sprachmodell Llama 3 mithilfe von Low-Rank Adaptation (LoRA) feinjustiert werden. Dazu werden strukturierte Trainingsdaten erstellt, in denen typische Interaktionen zwischen Lernenden und Tutoren dargestellt werden, inkl. Korrekter und falscher Antworten. Die Modelle lernen dadurch, die Antworten der Studierenden zu bewerten und passende didaktische Reaktionen zu geben.

## Technologien
- Frontend in Unreal Engine 5
- Backend (Node.js + REST API)
- Sprach-KI auf DACHS-Cluster (LLaMA)
- Wissensbasis mit semantischer Suche (LangChain + FAISS)
- Datenerhaltung (PostgreSQL in Docker)