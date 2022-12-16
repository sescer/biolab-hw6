# biolab-hw6

Student: Patrushev Boris 19213
------
## Sequence

`MDKGDVTALPMKKWFTTNYHYLVPEVEPSAEIKLNSTKPFDEFNEAKSLGVETKPVFIGPYTFLKLARTPEAAELEIDKGLVNAVAAVYAEVLARFNDLG`

## Tools

- Folding Tool 1: OpenFold - [ipynb](/openfold/OpenFold.ipynb), [pdb-output](/openfold/openfold.pdb)
- Folding Tool 2: OmegaFold - [ipynb](/omegafold/omegafold.ipynb), [pdb-output](/omegafold/omegafold.pdb)
- Pair Alignment Tool: [MASS](http://bioinfo3d.cs.tau.ac.il/MASS/server.html)- [output with logs](/mass) (you can use [archive.zip](Archive.zip) to upload on web server to check output) 
- Vizualization Tool: [Jmol](https://jmol.sourceforge.net/)

## Pair Alignment

It was hard to set up jmol for this task, so If you want to repeat the process, just copy the commnad bellow

`load openfold.pdb;color orange;ribbons only;load append omegafold.pdb;select 2.1;color yellow;ribbons only;frame *;`

For rotating you must select the model and then rotate with mouse:

`select 1.1; set  set allowRotateSelected true; set dragSelected true;`

Output:
![](/images/out.gif)
![](/images/out_mass.gif)


## Conclusion
If you look at the visualization, you can see that the structure is very similar to each other, but there are slight differences.
