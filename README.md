# WEBGRAPH
Cette commande, écrit en Pascal (Turbo Pascal ou Free Pascal), permet d'afficher un graphique en toile d'araignée à partir de données.

<h3>Syntaxe</h3>

<b>WEBGRAPH</b> [/FORMAT:SVG] <i>source.csv</i> [<i>target.svg</i>]

<h3>Paramètres</h3>

<table>
		<tr>
			<th width="150px">Nom</th>
			<th>Description</th>
		</tr>	
		<tr>
			<td><i>fichier</i>.CSV</td>
			<td>Ce paramètre permet d'indiquer le nom du fichier a analyser.</td>
		</tr>
		<tr>
			<td><i>target.svg</i></td>
			<td>Ce paramètre permet d'indiquer le nom du fichier allant contenir le SVG.</td>
		</tr>
		<tr>
			<td><b>/FORMAT:SVG</b></td>
			<td>Ce paramètre permet de sortir le résultat en format SVG.</td>
		</tr>
</table>

<h3>Remarques</h3>

<ul>
		<li>Si le format de sortie n'est pas indiqué par le paramètre <i>/FORMAT</i>, il affichera le résultat à l'écran.</td>
		<li>Le nombre de sommet est calculé en fonction du nombre de ligne que contiendra le fichier .CSV.</li>
		<li>Le fichier .CSV à analyser ne doit pas contenir de ligne d'entête et il doit être une suite de texte et de valeur séparé par une virgule. La valeur doit être comprise entre 1 et 5.</li>
</ul>

<h3>Exemples</h3>
 
Prenons pour acquis que le fichier <i>graph.csv</i> à la contenu suivant&nbsp;:

Combatif,3<br />
Courageux,4<br />
Innovateur,2<br />
Precurseur,5<br />
Talentueux,1<br />

L'exemple suivant permet de lancer la commande avec le fichier <i>graph.csv</i>&nbsp;:

<b>WEBGRAPH</b> graph.csv			

on obtiendra le résultat suivant&nbsp;:
 
![webgraph-1](https://github.com/gladir/WEBGRAPH/assets/11842176/cb995b1d-f552-4f3e-b49d-c324029b8d72)

Prenons pour acquis que le fichier <i>graph2.csv</i> à la contenu suivant&nbsp;:

Combatif,3<br />
Courageux,4<br />
Innovateur,2<br />
Precurseur,5<br />
Talentueux,1<br />
Arrogant,5<br />
 
L'exemple suivant permet de lancer la commande avec le fichier <i>graph2.csv</i>&nbsp;:
 
<b>WEBGRAPH</b> graph2.csv			

on obtiendra le résultat suivant&nbsp;:
 
![webgraph-2](https://github.com/gladir/WEBGRAPH/assets/11842176/a68db17d-e6d3-4e76-9a1d-b0d8d21a2654)
