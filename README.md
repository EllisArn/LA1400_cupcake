# Winforms

Ich habe mit meiner Gruppe mit Winforms ein Hütchenspiel gemacht. Wir haben dafür hauptsächlich Buttons, Labels, textBoxen und pictureBoxen benutzt.


## Ziele

Ich weiß, wofür man die 3 Tools benutzen kann.

Ich weiß, wie ich die 3 Tools sinnvoll implementieren kann.

Ich kann die 3 Tools benutzen.

## Erklärung


### Button

Ein Button (Knopf) führt einen Code aus, sobald man diesen drückt. Im Winforms-Code sieht das so aus:
```csharp
public void button1_Click(object sender, EventArgs e)
{
    // Code, der beim drücken ausgeführt werden soll
}
```
Das Innere des Buttons ist ein ganz normaler Code, der nur ausgeführt wird, wenn man den Button drückt.


### Label

Ein Label ist einfach ein Behälter, der Text anzeigen kann. Er kann zwar auch ein Bild anzeigen, aber dafür würde ich eher eine pictureBox nehmen.
Hier im Beispiel wird der Code ausgeführt, wenn der Text im Label verändert wurde. Im Winforms-Code sieht das so aus:
```csharp
private void label1_TextChanged(object sender, EventArgs e)
{
    // Code, der beim ändern des Textes ausgeführt weden soll
}
```


Mit `label1.Text = "";` kann man den Text im Label, z.B. wenn der Knopf gedrückt wird, ändern. Das sieht dann so aus:
```csharp
public void button1_Click(object sender, EventArgs e)
{
    label1.Text = "Hallo";
}
```
Jetzt würde, wenn man den Knopf drückt, der Text im Label zu "Hallo" ändern.


### textBox

Eine textBox ermöglicht es dem Benutzer Text einzugeben, den das Programm benutzen kann.
Ich habe in dem Beispiel ein Label, ein Button und eine textBox benutzt.
```csharp
public void button1_Click(object sender, EventArgs e)
{
    label1.Text = textBox1.Text;
}
```
Jetzt kann der Benutzer etwas in die textBox eingeben, dann den Button klicken und dann wird das, was er eingegeben hat im Label stehen.


### pictureBox

Eine pictureBox ist dazu da, ein Bild anzuzeigen. Ich habe in dem Beispiel einen Button benutzt, und `pictureBox1.Visible` benutzt.
```csharp
private void button1_Click(object sender, EventArgs e)
{
    pictureBox1.Visible = false;
}
```
Jetzt wird die pictureBox versteckt, sobald man den Button drückt.


## Bild & Video

![image](https://user-images.githubusercontent.com/89130718/147253429-62e53aaa-25fd-49e6-958e-ef525724d487.png)

[Video](https://www.youtube.com/watch?v=hF94VTPIyFs)


## Verifikation

Ich habe es einem Mitschüler gezeigt und er hat gesagt, dass mein Portfolio das Thema gut erklärt.

## Reflexion & VBV

Für mich war das Schwerste, den Rekord in einer Datei zu speichern, aber darüber werde ich hier nicht schreiben. Ich habe das Problem zwar irgendwie gelöst, aber ich war nicht wirklich zufrieden. Deshalb will ich dem noch nachgehen. Ausserdem war die Kommunikation in der Gruppe etwas schwer. Die will ich beim nächsten Mal auch noch verbessern.

