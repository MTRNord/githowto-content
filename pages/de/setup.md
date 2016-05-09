---
view: page
title: "1. Vorbereitung"
---

<h3>Ziele</h3>

<ul><li>Vollst&auml;ndig auf die Arbeit mit Git borbereitet zu sein.</li></ul>

<h2><em>01</em> Einstellen von Name und E-Mail Adresse</h2>

<p>Wenn du vorher nie Git genutzt hast musst du zuerst deinen Namen und deine E-Mail einrichten. F&uuml;hre die folgenden Befehle aus, um Git zu sagen, wie dein Name und deine E-Mail Adresse lauten. Falls Git bereits installiert ist, kannst du diesen Schritt &uuml;berspringen.</p>

<h4 class="h4-pre">Ausf&uuml;hren:</h4>

<pre class="instructions">git config --global user.name "Dein Name"
git config --global user.email "deine_email@irgendwas.com"</pre>

<h2><em>02</em> Installation Optionen Zeilen Enden</h2>

<p>Also, f&uuml;r Unix/Mac Benutzer:</p>

<h4 class="h4-pre">Ausf&uuml;hren:</h4>

<pre class="instructions">git config --global core.autocrlf input
git config --global core.safecrlf true</pre>

<p>F&uuml; Windows Benutzer:</p>

<h4 class="h4-pre">Ausf&uuml;hren:</h4>

<pre class="instructions">git config --global core.autocrlf true
git config --global core.safecrlf true</pre>
