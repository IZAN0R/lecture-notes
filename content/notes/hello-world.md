---
title: "hello world"
date: 2023-09-18T07:44:00+07:00
authors: ['IZAN0R']
tags: ['not for sale']
draft: false
math: true
url: "0048"
---
{{< toc >}}


## Lambang
![](https://2.bp.blogspot.com/-mYayuRn99Qg/U_QfS_LHmlI/AAAAAAAAEko/kY8Nm5HoyUs/s1600/akademi-kepolisian-logo.png)


## Sejarah Singkat
[https://akpol.ac.id/sejarah-singkat/](https://akpol.ac.id/sejarah-singkat/)


## Jumlah Penerimaan Taruna
{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['2018', '2019', '2020', '2021', '2022', '2023'],
        datasets: [{
            label: 'Bar Chart',
            data: [100, 150, 200, 250, 300, 300],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}


## Taruna AKPOL
 + Kepangkatan Taruna
	- Batalyon X (Tk. I)
	- Adhi Wiratama (Tk. II)
	- Presisi (Tk. III)
	- Satya Dharma (TK. IV)


## Kegiatan Taruna
{{< youtube t2k3uwS2zyA >}}


## Rencana Kegiatan
No. | Waktu | Kegiatan
:-: | :-:| :-
1| 04.30 | Taruna melaksanakan Sholat Subuh
2| 05.00 | Taruna Melaksanakan Olahraga Pagi
3| 05.40 | Taruna Melaksanakan Pembersihan Mandiri
4| 06.30 | Taruna Melaksanakan Apel Makan Pagi
5| 07.00 | Taruna Melaksanakan Apel Pagi
6| 08.00 | Taruna Melaksanakan perkuliahan
7| 12.30 | Taruna Melaksanakan Makan Siang
8| 14.00 | Taruna Melaksanakan Unit Kegiatan Taruna
9| 17.00 | Taruna Melaksanakan Pembersihan Mandiri
10| 18.15 | Taruna Melaksanakan Makan Malam
11| 19.30 | Taruna Melaksanakan Belajar Mandiri
12| 21.00 | Taruna Melaksanakan Apel Malam
13| 22.00 | Taruna Melaksanakan Istirahat Malam



## Proses 
{{< mermaid >}} 
flowchart LR
	Pdft --> LS --> Pdk --> L --> Pmpt 
	Pdft(("Pendaftaran"))
	LS[/"Lolos Seleksi"/]
	Pdk["Pendidikan"]
	L[/"Lulus"/]
	Pmpt(("Penempatan"))
{{</ mermaid >}}

## LaTex
$$ E = mc^2 $$


## Quote
> Kepala tanpa pengetahuan adalah seperti benteng tanpa prajurit. -izanor


## SVG Image with animation
{{< html >}}
<svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with animation -->
  <rect x="10" y="10" width="50" height="50" fill="blue">
    <animate attributeName="width" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="height" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="fill" values="blue;red;green;blue" dur="4s" begin="0s" repeatCount="indefinite" />
  </rect>
</svg>
{{< /html >}}
