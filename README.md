Diese Analyse beinhaltet drei Dateien:

LoL_champion_data.csv - die CSV Datei, aus welcher die Informationen, welche in der Analyse verwendet werden, aufgelistet sind
(Erhalten von https://www.kaggle.com/datasets/laurenainsleyhaines/25-05-league-of-legends-champion-data-2025/data)

League of Legends Champion Analyse.ipynb - Ein Jupyter Notebook File, welches die Analyse an sich beinhaltet. 
Diese Analyse wurde hauptsächlich mithilfe von Python, Pandas sowie Matplotlib/Seaborn-gestützen Graphen durchgeführt. 
Die im Laufe der Analyse durchgeführten Schritte sind hierbei ausgiebig von Klartexterklärungen unterstützt, damit diese leichter nachzuvollziehen sind

LoL Champion Data.pbix - Eine Microsoft Power BI Datei, in welcher zusätzliche Analytische Untersuchungen durchgeführt wurden.
Hierbei decken sich manche Untersuchungen mit gleichen Analysepunkten aus der Python Datei, es befinden sich jedoch noch weitere zusätzliche Untersuchungen in dieser Datei, wie eine Aufteilung der Champion-Attribute auf die einzelnen Klassen der Charaktere.
WICHTIG: Damit diese Power BI Datei ausgeführt werden kann, muss dass .ipynb Python File vorher durchgeführt werden, da im Laufe dieses Python Files die beiden zusätzlichen .csv Dateien, auf welche sich die Power BI Analyse stützt, erstellt werden.
