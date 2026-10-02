# Modul [02] - MENCARI FAKTOR BILANGAN]

**Nama:** [Muhammad Iqbal]  
**NIM:** [1306625004]  
**Kelas:** [FISIKA-C]  

---

## 1. Problem Statement
> Membuat program yang dapat mencari seluruh faktor dari input bilangan positif

## 2. Mathematical Equation
> $$\text{bilangan} \bmod \text{calon faktor} = 0$$

## 3. Algorithm
> 1. start
> 2. print"Program Himpunan Faktor Dari Bilangan Bulat Positif"
> 3. Print "Nama: Muhammad Iqbal"
> 4. Print "NIM:1306625004"
> 5. Def mencari faktor
> 5. 1. True, inloop
>    2. Input "bilangan positif:  "
>    3. Bialngan <= 0?
>    3. 1. tidak, print"Bilangan harus lebih besar dari 0", kembali ke 5.2
>       2. ya,  lanjut dan buta list faktor
>    4. Faktor[ ]
>    5. Calon_Faktor in range (1, bilangan+1)
>    5. 1. Bilangan % Calon_Faktor
>       2. 1. Bilangan % Calon_Faktor=0?
>          2. 1. ya, Faktor.append(Calon_Faktor)
>             2. tidak, false dan lanjut
>          3. Calon_Faktor+1, loop back ke 5
>    6. print(f"Himpunan faktor dari {Bilangan{} adalah {Faktor}")
>    7. Ulangi= Input("Apakah anda ingin mencari himpunan faktor suatu bilangan lagi? (ya/tidak):  ")
>    8. Ulangi=tidak?
>    8. 1. tidak, ulangi program ke 5. dalam kondisi true
>       2. ya. kembali ke program algoritma 5. dalam kondisi false break lalu ke 5.9
>    9. break, false, outloop
> 6. print"Terimakasih telah menggunakan program ini"
> 7. Selesai
>
>" "
> [Flowchart_Mencari Faktor Bilangan.drawio](https://github.com/user-attachments/files/32940635/Flowchart_Mencari.Faktor.Bilangan.drawio)
> [Uploading Flowchart_Mencari Faktor Bilangan.drawio…]()
<mxfile host="app.diagrams.net">
  <diagram name="Page-1" id="ws9HsZFQrsQNzq8FjP71">
    <mxGraphModel dx="693" dy="313" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="XICCi60GkelztMXWJWBX-3" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-2" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-1" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="Start" vertex="1">
          <mxGeometry height="70" width="120" x="360" y="10" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-5" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-4" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-2" parent="1" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;shapeInside=1;fixedSize=1;" value="print &quot;Program himpunan faktor dari bilangan bulat positif&quot;&lt;div&gt;&lt;br&gt;&lt;/div&gt;" vertex="1">
          <mxGeometry height="60" width="190" x="325" y="110" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-7" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-6" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-4" parent="1" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;shapeInside=1;fixedSize=1;" value="&lt;div&gt;&lt;br&gt;&lt;/div&gt;&lt;div&gt;print &quot;nama&quot;&lt;/div&gt;" vertex="1">
          <mxGeometry height="60" width="120" x="360" y="190" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-9" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-6" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-8" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-6" parent="1" style="whiteSpace=wrap;html=1;" value="print &quot;NIM" vertex="1">
          <mxGeometry height="60" width="120" x="360" y="270" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-11" edge="1" parent="1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" value="Ya, True">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="419" y="410" as="sourcePoint" />
            <mxPoint x="419" y="450" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-71" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-8" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="WtNzr6ajPcRTg4p7H7lh-1" value="Break, Outloop">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="560" y="380.03" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-8" parent="1" style="shape=process;whiteSpace=wrap;html=1;backgroundOutline=1;" value="Mencari Faktor" vertex="1">
          <mxGeometry height="60" width="120" x="360" y="350" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-15" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-10" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-14" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-10" parent="1" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;shapeInside=1;fixedSize=1;" value="Input &quot;Bilangan positif:&amp;nbsp; &quot;" vertex="1">
          <mxGeometry height="60" width="120" x="360" y="450" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-17" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-14" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-16" value="Tidak">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-25" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-14" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-24" value="Ya, buat faktor list">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-14" parent="1" style="rhombus;whiteSpace=wrap;html=1;shapeInside=1;" value="Bilangan &amp;lt;= 0?" vertex="1">
          <mxGeometry height="100" width="120" x="360" y="540" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-19" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-16" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-18" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-16" parent="1" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;shapeInside=1;fixedSize=1;" value="print &quot;Bilangan harus lebih besar dari 0&quot;" vertex="1">
          <mxGeometry height="60" width="120" x="160" y="560" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-18" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="1" vertex="1">
          <mxGeometry height="30" width="30" x="205" y="640" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-23" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-20" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="XICCi60GkelztMXWJWBX-10">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-20" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="1" vertex="1">
          <mxGeometry height="30" width="30" x="310" y="420" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-28" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-26" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-24" parent="1" style="whiteSpace=wrap;html=1;" value="Faktor [ ]" vertex="1">
          <mxGeometry height="60" width="120" x="360" y="690" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-30" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-26" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-29" value="True, inloop">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-45" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-26" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="PpHtyCdsfBzStBB2lE4c-1" value="False, Outloop">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="590" y="830" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-26" parent="1" style="shape=hexagon;perimeter=hexagonPerimeter2;whiteSpace=wrap;html=1;shapeInside=1;fixedSize=1;" value="Calon Faktor&amp;nbsp;in range(1, Bilangan + 1)" vertex="1">
          <mxGeometry height="80" width="120" x="360" y="790" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-32" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-29" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-31" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-29" parent="1" style="whiteSpace=wrap;html=1;" value="Bilangan % Calon Faktor" vertex="1">
          <mxGeometry height="60" width="120" x="360" y="920" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-34" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-31" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-33" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-35" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-31" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-33" value="Ya">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-37" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-31" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-36" value="Tidak">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-31" parent="1" style="rhombus;whiteSpace=wrap;html=1;shapeInside=1;" value="Bilangan % Calon_Faktor == 0?" vertex="1">
          <mxGeometry height="110" width="150" x="345" y="1010" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-38" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-33" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="XICCi60GkelztMXWJWBX-36">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <UserObject label="Faktor.append(Calon_Faktor)" id="XICCi60GkelztMXWJWBX-33">
          <mxCell parent="1" style="whiteSpace=wrap;html=1;" vertex="1">
            <mxGeometry height="60" width="180" x="100" y="1035" as="geometry" />
          </mxCell>
        </UserObject>
        <mxCell id="XICCi60GkelztMXWJWBX-41" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-36" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-40" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-36" parent="1" style="whiteSpace=wrap;html=1;" value="Calon Faktor + 1" vertex="1">
          <mxGeometry height="60" width="120" x="360" y="1200" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-39" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-36" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;innerLoopWaypoints=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;" target="XICCi60GkelztMXWJWBX-36">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-40" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="2" vertex="1">
          <mxGeometry height="40" width="40" x="400" y="1300" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-43" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-42" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" target="XICCi60GkelztMXWJWBX-26">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-42" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="2" vertex="1">
          <mxGeometry height="40" width="40" x="260" y="740" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-48" edge="1" parent="1" source="PpHtyCdsfBzStBB2lE4c-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;" target="XICCi60GkelztMXWJWBX-47" value="">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="660" y="860" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-52" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-47" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-51" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-47" parent="1" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;shapeInside=1;fixedSize=1;" value="ulangi = input(&quot;Apakah Anda ingin mencari himpunan faktor suatu bilangan lagi? (ya/tidak): &quot;)" vertex="1">
          <mxGeometry height="100" width="190" x="565" y="900" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-53" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-51" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" target="XICCi60GkelztMXWJWBX-56" value="ya">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="570" y="1130" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-59" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-51" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-58" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-51" parent="1" style="rhombus;whiteSpace=wrap;html=1;shapeInside=1;" value="ulangi = tidak?" vertex="1">
          <mxGeometry height="80" width="80" x="620" y="1035" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-56" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="4" vertex="1">
          <mxGeometry height="40" width="40" x="550" y="1130" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-61" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-58" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-60" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-58" parent="1" style="whiteSpace=wrap;html=1;" value="Ulangi Program" vertex="1">
          <mxGeometry height="60" width="120" x="720" y="1045" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-60" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="3" vertex="1">
          <mxGeometry height="40" width="40" x="760" y="1130" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-65" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-62" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.75;entryDx=0;entryDy=0;" target="XICCi60GkelztMXWJWBX-8">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-62" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="3" vertex="1">
          <mxGeometry height="40" width="40" x="240" y="370" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-68" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-66" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-67" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-66" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="4" vertex="1">
          <mxGeometry height="40" width="40" x="270" y="190" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-69" edge="1" parent="1" source="XICCi60GkelztMXWJWBX-67" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0;entryY=0.25;entryDx=0;entryDy=0;" target="XICCi60GkelztMXWJWBX-8">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-67" parent="1" style="whiteSpace=wrap;html=1;" value="Break" vertex="1">
          <mxGeometry height="60" width="120" x="230" y="270" as="geometry" />
        </mxCell>
        <mxCell id="XICCi60GkelztMXWJWBX-72" parent="1" style="ellipse;whiteSpace=wrap;html=1;shapeInside=1;" value="Selesai" vertex="1">
          <mxGeometry height="80" width="100" x="610" y="450" as="geometry" />
        </mxCell>
        <mxCell id="PpHtyCdsfBzStBB2lE4c-1" parent="1" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;shapeInside=1;fixedSize=1;" value="print(f&quot;Himpunan faktor dari {Bilangan} adalah {Faktor}&quot;)" vertex="1">
          <mxGeometry height="70" width="140" x="590" y="795" as="geometry" />
        </mxCell>
        <mxCell id="WtNzr6ajPcRTg4p7H7lh-2" edge="1" parent="1" source="WtNzr6ajPcRTg4p7H7lh-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" target="XICCi60GkelztMXWJWBX-72" value="">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="WtNzr6ajPcRTg4p7H7lh-1" parent="1" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;shapeInside=1;fixedSize=1;" value="print &quot;Terima kasih telah menggunakan program ini.&quot;" vertex="1">
          <mxGeometry height="60" width="120" x="600" y="350" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>

