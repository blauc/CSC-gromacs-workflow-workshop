---
title : PRACE, CSC / BioExcel workshop - GROMACS workflows and advanced topics 
---

# CSC / BioExcel workshop - GROMACS workflows and advanced topics 

The place for all [workshop](https://events.prace-ri.eu/event/1148/) information that you can edit [here](https://hackmd.io/KM--J8wsRIWQ2EU_Tgd5SA/edit) using [hackmd](https://hackmd.io/c/tutorials). Ask questions at the very bottom of this [page](#Questions)!

---

[TOC]

## Code of Conduct

We strive to follow the Code of Conduct developed by The Carpentries [organisation](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html) to foster a welcoming environment for everyone. In short:

- Use welcoming and inclusive language
- Be respectful of different viewpoints and experiences
- Gracefully accept constructive criticism
- Focus on what is best for the community
- Show courtesy and respect towards other community members



# Before the workshop

Let us know something [about you](#About-you).

## Things to watch

We suggest you watch the recorded lectures before the tutorials to make it easier for you to follow and make the most of time with the traininers. We will recap things briefly before each session.

#### QM/MM 

:::spoiler
[QM/MM intro lecture Part 1 (30 min)](https://embl-ebi.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=eccb096a-20d8-49ac-9bd3-abce01617b1f)
[QM/MM intro lecture Part 2 (30 min)](https://embl-ebi.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=05f3c329-bf92-4883-bdc3-abce01617aa0)

Also available on youtube ([Part 1](https://www.youtube.com/watch?v=kZrGWcVcuFM) and [Part 2](https://www.youtube.com/watch?v=Y5Uy4y86Yus)).

:::

#### Free energies with pmx

[Free energy calculations with pmx (60 min)](https://www.youtube.com/watch?v=XLCxm7HcDFo)


## Things to prepare on your computer

:::spoiler

### Installing a current GROMACS version and python packages


Please follow these installation [instructions](https://blauc.github.io/gromacs-workshop-installation/)

- Make sure you have a working ssh client

### Software check

 - Help with software installation requirements
 - Thursday 2021-01-28 15:00-17:00 (CET) in [zoom meeting room 651 4521 0767](https://kth-se.zoom.us/j/65145210767?pwd=dmVZUWZqQ2xCdnRJQjkxcUwwWXFZdz09) with password `csc`.

:::

## Send your flash talk slide

:::spoiler

 - Monday program culminates in flash (3 minutes strict maximum) introductions
 - Send your presentation (1 slide is enough / recommended, in pdf format) by Friday 29th Jan to atte.sillanpaa@csc.fi
 - Participation in the workshop requires providing the slide
:::

# At the workshop

## Connecting

 - Socialise on [gather town](https://gather.town/app/sqdvaCkg50dfNwK2/advanced-gromacs) after lectures or during lunch
 - Connect to lectures and workshop via [zoom meeting room 651 4521 0767](https://kth-se.zoom.us/j/65145210767?pwd=dmVZUWZqQ2xCdnRJQjkxcUwwWXFZdz09) with password `csc`.
  
## Schedule

:::info
All times in CET
:::

| CET           |                                                                                        |                                |
| ------------- | -------------------------------------------------------------------------------------- | ------------------------------ |
| **Day 0**     | Thursday                                                                               | 2021-01-28                     |
| 15:00-17:00   | [Software requirements check](#Software-check)                                         | Christian Blau                 |
| **Day 1**     | Monday                                                                                 | 2021-02-01                     |
| 9:00 –  9:30  | [Introduction](#About-you), organization                                               | Christian Blau, Atte Sillanpää |
| 9:30 – 11:30  | [QM/MM](#QMMM) simulations with GROMACS and CP2K                                       | Dmitry Morozov                 |
| 11:30 – 12:30 | Lunch break                                                                            |                                |
| 12:30 - 14:00 | [Participant flash talks](#Participant-flash-talks) on their research and/or interests |                                |
| 14:00 - ...   | hangout in [gather](##Connecting) / Q&A with Dmitry                                    |                                |
| **Day 2**     | Tuesday                                                                                | 2021-02-02                     |
| 9:00–11:30    | HPC workflows with GROMACS supported by BioBB - bioexcel building blocks / PyCOMPSs    | Adam Hospital                  |
| 11:30 – 12:30 | Lunch break                                                                            |                                |
| 12:30–14:00   | GROMACS - Python down to the metal interface for in-memory toolchains with GROMACS     | Eric Irrgang                   |
| 14:00 - ...   | hangout in [gather](##Connecting) / Q&A                                                |                                |
| **Day 3**     | Wednesday                                                                              | 2021-02-03                     |
||||
| 09:00–11:30   | [pmx](#PMX) - free energy calculations                                                 | Yuriy Khalak, Vytautas Gapsys  |
|11:30–12:30|Lunch break| | |
| 12:30-14:00   | Performant setup GROMACS on GPUs                                                       | Christian Blau                 |
| 14:00-14:15   | Wrap-up / feedback                                                                     |                                |
| 14:15 - ...   | hangout in [gather](##Connecting) / Q&A                                                |                                |


## About you

| Name | interests | something about *you*
|---|---|---
|Christian Blau | GROMACS code development, combining simulation and experimental data (mainly cryo-EM), statistical physics | Started career in Göttingen, now in Stockholm
|Dmitry Morozov| QMMM code development in Gromacs, reactions in condesed phases, enzymes and photochemical/photobiological systems | Received PhD from Moscow State University, then moved to University of Jyväskylä, now working within the Bioexcel-2 CoE
|M. Eric Irrgang| Python as glue between high performance C++ libraries; improving the application of modern computing resources to scientific software | Research scientist in Kasson Lab at University of Virginia |
|Atte Sillanpää| Support researchers in using HPC in chemistry and all disciplines. Workflows, clever data management and sharing next big things in addition getting maximum performance from hardware |CSC development manager, background in computational chemistry. Beach volley at free time |
|Adam Hospital| Biomolecular simulation workflows. Tools interoperability. HPC and HT biomolecular simulations | Background in Computational science, PhD in BioTechnology, leading the BioExcel-2 workflows team. VideoGames in my free time (free time??)|
|Vytautas Gapsys| Molecular dynamics simulations. Alchemical free energy calculations. pmx development | Background in computational biophysics and basketball.

#### Training account assignment 

Claim one of the accounts below, and replace XXX above with that number. Use that account for the rest of the workshop. Password is given in the chat.

- training008 _Write your name here to claim the account_
- training009 ...

Change to the scratch area and make a folder for yourself:
```bash=
cd /scratch/project_2000745
mkdir trainingXXX # replace the XXX with your account number
cd trainingXXX # same
```
## Using GPUs

**Use [Puhti](https://docs.csc.fi/computing/systems-puhti/)**
- [Information on GROMACS on Puhti](https://docs.csc.fi/apps/gromacs/)

Then use ssh to connect to Puhti, like

`ssh training0XX@puhti.csc.fi`

The same password as yesterday is used (pasted in the Zoom chat).

:::danger
All work on Puhti should be done in the scratch folder, which is visible to all compute nodes. You might need to
make your own working directory if it's not already there. The inputs for today's exercises are found in an archive file that you can then unzip:
```bash=
cd /scratch/project_2000745
mkdir training0XX # if not already existing
cd training0XX
wget https://kth.box.com/shared/static/4dp0kbeasgesusedua3mu50vn1tk4rjw.gz
```
:::

Note: Edits for the batch scripts (add this to all batch scripts):
```
#SBATCH --nodes=1
```

#### Q&A

- how do you know that ntasks=1 and tasks-per-node=10 is the optimal solution? So if I wanted eg 4 gpus I would use 4 tasks?
> With the CSC hardware there are 4 GPU cards per node and 40 cpu cores. As shown in the hardware topology 10 cpu cores are optimally positioned to access the GPU. Also, not requesting more than 10 cores will allow others to use the other GPU cards. Still, in more fundamental perspective, it's hard to say in advance so you could/should try and look at the performance. Generally it will be more efficient to use 1 GPU per simulation but run more simulations in parallel. Using more than 1 GPU per simulation needs extra tweaking.

## PMX

Let's use the "develop" branch of pmx for this tutorial.
The installation instructions can be found here: 
https://github.com/deGrootLab/pmx/blob/develop/tutorials/INSTALL


#### Q&A

- GROMACS seems to run slower on free energy calculations - even if I don't perturb the system (lambda = 0 or 1)?
> That is true. Things are improving with newer versions of GROMACS, but there is still a penalty in these runs, because we use less specifically optimized compute routines that allow for interpolation between topologies even here and calculate the dH/dlambda values.
- Why not just run without lambda
> That works as well. You would have to create a different topology for lambda = 1 and you won't get dH/dlambda values, but otherwise you are good to go.
- What about newer amber force-fields - they do not seem to be implemented in pmx?
> pmx itself does not implement force-fields - you can use any all-atom force-field that GROMACS can run
- What about the newest amber force-fields in GROMACS
> There is an issue with furhter CMAP corrections for specific amino-acids - these are not supported by GROMACS at the moment.
- How about protein post translational modifications? For example acetylated Lys. Is it straightforward to prepare hybrid topology if I have parameterized the modified residue?
> If you extract only the Lys from the topology (with temporary capping of the peptide bonds) and similarly extract the acetylated form, you could feed them to pmx as if they were ligands. The resulting mixed topology can be inserted back into the protein topology.
- What is the difference btw non equilibrium and equilibrium free energy calculation approach?
> Equilibrium approaches simulate equilibria of all the intermediate states and for good convergence need structural overlap between neighboring states. Non-equilibrium approach instead captures these intermediate states by running many short transitions from end state A to B and from B to A.
> Alternatively, if you do not want to run more repeats, the pmx analysis script also can do bootstrapping of the available work values (optional parameter) to produce an error estimate that is closer to the real uncertainty.
- How to estimate appropriate ddG calculation error? E.g. we made the calculations and got ddG = -1 ± 0.3 kJ/mol. Are there ways to say if it physically meaningful or we just heating the atmosphere? 
> In my experience, run multiple repeats. The analytical error the BAR estimator reports is typically an overestimation of the true uncertainty. 
- Would gmx 2020.4 be sufficient? Do not want to reinstall the environment 
> Yes, 2020.4 is usually sufficient for running through the tutorial. 2020.5 received some bugfixes https://manual.gromacs.org/2020.5/release-notes/2020/2020.5.html - so in general it's a good idea to run with the latest GROMACS.
- Are there any limitations considering ligand morphing?
> Yes, there are some hard-coded rules. pmx will not morph between ring and non-ring atoms, will avoid bond-breaking (not generating disconnected fragments). Better not to morph between light hydrogen atoms and heavy atoms. If there is a very large pertubation it's not a limitation to pmx itself, but the simulation will not converge; might have to run much slower.
- Tried my best during the break to find an error but for me fe.atom_mapping(bVerbose=True) does not work in Jupyter? I get an error b"NameError: name 'Chem' is not defined” and so I can not go further
> try "conda install -c rdkit rdkit" from within the conda environment and restart the notebook 
- When preparing the simulation box. I came up with an error gmx executable not found. How can I fix it? 
> the gromacs binaries need to be in $PATH when the notebook is launched, if using bash for example you can "source /path/to/gmx/installation/bin/GMXRC" to set all the appropriate environmental variables.
- Could you please enlighten us on the physical/technical origins of huge problem regarding charge non-conserving transformations, and what is your favorite way to combat it?
> When you transform between ligands with different net charges, you end up with a net charged system in at least one end state. Ewald-based long range electrostatics will have issues if the system has a net charge (there will be an effective canceling charge smeared across the whole simulation box). That's the origin of the issue. The solution I have used in the past was the double system single box approach: combine both the protein and water parts of the thermodynamic cycle in one simulation box, but separated by a large distance. Namely, ligand_A morphs into ligand_B in the active site while ligand_B simultaneously morphs into ligand_A in the solvent. This ensures the system charge is always constant. To prevent the unbound ligand interacting with the protein one should also restrain the two to be far apart. The downside is that one has to simulate a lot of extra solvent with this approach.
- For standard protein ligand simulation do we need to modified the ligand always for pmx calculations, or we can do it by modifying the certain aa residues?
> if you modify the ligand, you will have to find the parameters for the ligand and the modified ligand yourself, for amino-acids you can use some information that is pre-calculated and available within pmx
> You can also modify the amino acids instead of the ligand. You just need to make sure the thermodynamic cycle still gives you the deltaGs you are looking for. For example if you want the free energy difference for ligand binding to WT vs a mutant, you only need the protein part of the thermodynamic cycle
- Do you have a reference for proline in the database? 
> On the todo list, depends on using the pmx develop branch
- How can we handle gromacs run parameters inside pmx? E.g. provide -ntmpi x -ntomp y options
> Can do that by updating the jobscripts
- In case of binding with ions, how can one obtain the parameters for ionic species? For example binding of RNA to Na+/Mg++ ions.
> Use the force-field parameters, for only chaning ion species, you can even just manipulate the topology by hand.
- Are you planning to provide support also for other force fields? For example, Amber14SB ?
> We support anything coming up, only limit is GROMACS support for the force-field.
- What barostats / thermostats are you using
> Barostats - the ones that reproduce physical behaviour. Thermostats can be tricky due to dummy atom acceleration, we use stochastic dynamics instead.
- What about free energy calculation performance on GPUs? 
> free energies on gpu: the free energy kernel itself is implemented for CPU only, therefore GPUs do not directly help to speed up this part of the simulation. The GPUs, of course help with the simulation speed of the rest of the system, but the CPU based free energy kernel remains the bottleneck 



# Questions

- Hi, is Gromacs version 2020.2 enough? Or do we have to install a newer version.
> 2020.2 is fine for most tutorial sessions - there had been some bugfixes that should not affect results in tutorials. Generally we would suggest to always use the latest version; for the sake of learning functionality, using 2020.2 is sufficient [name=Christian Blau]
- In notes in one case it asks for 2020.4 and in another for 2020.5.
> Thanks for pointing this out - can you let me know where you find that discrepancy? [name=Christian Blau]
> By following this link to go to Gromacs workshop installation instructions "https://blauc.github.io/gromacs-workshop-installation/". When you open the jupyter notebook tutorial it asks for Gromacs 2020.4. Again following the link in coda instructions it asks for 2020.5. But it's just a minor detail. All I wanted to know was if the 2020.2 version is suffiecient. Thanks

# Sessions
## QMMM

#### Preparation
Please watch [this](#Things-to-watch) before the tutorial.

The CP2K GROMACS interface will be available on Mahti, you will not have to install it yourself. 

#### Logging in Mahti

:::info
You will recieve the password to log in to **Mahti** on Monday morning.
:::

```sequence
Your Computer->Your Computer: open terminal
Your Computer->Mahti: ssh trainingXXX@mahti.csc.fi
Note over Mahti: On Mahti:\npatched GROMACS\nCP2K\ngmx_cp2k
```

```bash
ssh trainingXXX@mahti.csc.fi
```

#### Watch how to do this on youtube

https://www.youtube.com/watch?v=Y5Uy4y86Yus=ExhJusg5iD4



#### QMMM Tutorial Handbook
We will follow this [pdf](https://github.com/bioexcel/gromacs_cp2k_tutorial/raw/master/Tutorial_handbook.pdf) during the tutorial - note that we might update things; make sure to download again just before the tutorial starts.

#### Updating the run script

```bash=
sed -i 's/2003478/2003487/' run.sh
```

### Additional material

[Dmitris presentation](https://github.com/bioexcel/gromacs_cp2k_tutorial/raw/master/Introduction_to_QMMM-Tutorial-CSC.pptx)
[Best Practice Guide](https://docs.bioexcel.eu/qmmm_bpg/en/main/)

#### Q&A CP2K for QM/MM Workshop

- Hello, do I have to install gmx-cp2k locally for "QM/MM simulations with GROMACS and CP2K" part of the event?
> No, it is sufficient that you use `ssh` [name=Christian Blau]
- Also how can I find the password for Mahti?
> You will recieve the password tomorrow.[name=Christian Blau]
 - Will polarizable classic FF (eg AMOEBA) give a better outcome in these simulations than one with fixed SPC? 
> 
 - How many atoms can you include to the QM part?
> With CP2K you are mostly limited in the size of QM box rather than actual number of QM atoms. QM part could include large amount of atoms up to 200, sometimes even more
 - How do we choose the value of the pulling force? 
> The value of force will normally depend your reaction coordinate. For a dihedral rotation, you can choose the value based on the dihedral parameters in the force field or start with a high value of 500 kJ mol-1 nm-1 and lower to check if affects the results. If you are pulling an ion or a peptide then one might need much higher >1000 kJ mol-1 nm-1. 
 - Since PLUMED is compatible with both, cp2k and Gromacs, perhaps it is also fully functional for this QM/MM aproach?
> yes, as long as you use PLUMED features that only add additional forces to the system. If the topology is modified, there is no checking that the modifications don't interfere with QM/MM, so it's a bit tricky
 - Does QM and MM tokens in *.pdb are meaningful for CP2K or Gromacs? Or it is just for human reading? 
> The tokens are for parsing the system coordinates to CP2K with MM charges which are treated using the GEEP method. 
 - Does Gromacs still have native interface for Orca, and probably some other QM software? What are the alternatives for CP2K?
> No, there is only MiMic at the moment.
 - in run.sh what does OMP_PLACES do?
> This instructs the queuing system and Gromacs to place the threads correctly in the hardware. Omitting this, or choosing a bad option can kill perofmance completely. Note, in other (super)computers you might need different flags.
 - can cp2k run a qm only calculation?
> Yes, it is possible to run an independent QM calculation (no need of using the interface for such calculations).
 - Did we know reaction coordinate before the calculations? 
> Yes, that's a challengeing thing, though.
 - So normally CP2K would generate the input automatically, but here we want to use TDDTF so we provide our own input file? And TDDFT is needed for calculating the excitation energies of the system? 
 - So we have the deafult QM method or we have choise for others too?
> You can use any method that CP2K supports, GROMACS and CP2K are decoupled in this sense.
- Is there any optimum value for TDDFT excitation energy for these types of calculation?
> I think it is up to user to decide wether energies is good or not. Best thing is always to compare with experimental absorption spectra and benchmark different DFT functionals.
- Will you provide `*.inp` files with your comments? There are no comment sections in tutorial files 
> In the presentation all input sections are comented:
https://github.com/bioexcel/gromacs_cp2k_tutorial/raw/master/Introduction_to_QMMM-Tutorial-CSC.pptx
- Does chosen classical FF influence on parameter set for QM and *vice versa*? How to combine them correctly?
> Practically they are not connected, you can use any forcefield you want, i.e. CHARMM or Amber. As for now, there is no direct influence between QM parameters and MM forcefield.


## Biobb


```sequence
Your Computer->Your Computer:
Note over Your Computer: open terminal\nconda activate biobb_Protein-Complex_MDsetup_tutorial\n...
```

Please watch the 
[Protein-Ligand Complex GROMACS Setup](http://mmb.irbbarcelona.org/biobb/workflows/tutorials/protein-complex_md_setup) and follow the instructions to reproduce the Jupyter Notebook in your own machines.

[Main Web Page](http://mmb.irbbarcelona.org/biobb/)
[Slides](http://mmb.irbbarcelona.org/biobb/documentation/online-info)
[Intro](https://drive.google.com/file/d/1dW8tF_3A7iBghw4_Fq0YU6ynlmh-5rvT/view?usp=sharing)
[Tutorial](https://drive.google.com/file/d/1hy6Nm6BjslZ1kVt1GaNt0q7ov9GHtuz4/view?usp=sharing)

#### Q&A

- Are these tutorials available in Biobb website? 
  > Yes, have a look here http://mmb.irbbarcelona.org/biobb/workflows
- Is it possbile to easily customise these workflows?
  > as they are available in jupyter, you can modify whatever you want 
- How and when cite biobb?
  > It's mentioned here: http://mmb.irbbarcelona.org/biobb/documentation/faqs 
- ok, many times we prepare the system locally but then simulation need to do on csc resources or how it is possbile to link our local envirnoment to HPC without downloading the files locally. Is it posssbile through jupyter notebook? 
  > It's possile to run the whole thing in HPC environment, too. At CSC, we'll look into making this easy and efficient. Perhaps either a centralized conda environment of a container with examples for using it would be a good start. 
- Is it possible (or does it make sense) to run the biobb machinery in a container in a HPC environment (set up by the HPC staff to avoid N separate installations)?
  > Can be done, but it can end up being a very large container... BioBBs are installed in BSC MareNostrum supercomputers as a module, with conda packages, and are working really well so far. 
- Do BB allow to avoid writing intermediate files during pipeline? E.g. `*.gro` files during structure preparation?
  > Not directtly, though there are workarounds: biobb's are wrappers and from the python code we launch binaries in this case gromacs if gromacs (in this case) just interacts with files and not programming objects we have to create the files in the cases were we are wrapping python libraries or inhouse soft, just in this cases we can avoid the use of files.
  > The Python API (gmxapi) can avoid this as it works directly in memory, but is, as of now, not a BioExcel building block.
  > Also python’s io.BytesIO could be a solution
- Where do I find the Covid related research (eg the RBD related one)?
  > It's currently being published - will be shared as soon as this is released, together with the building blocks that were used.
- Is PyCOMPSs also capable of GPU parallelisation
  > As far as the tool that you use can do GPU parallelisation, biobb can make use of that via the tool
- Why are the output cells highlighted in red?
  > That's a known issue - nothing is off, just the way it is implemented. There is a workaround that might be applied to all building blocks.
- How does biobb interface the queing system? There's one big allocation which biobb uses for the individual tasks? Are the individual tasks separate job steps (in slurm speak)?
  > BioBB is not interfacing the queuing system, in the pre-exascale examples PyCOMPSs is the one taking care of that. In the COVID-19 research examples presented, PyCOMPSs is queueing just one job in the slurm manager, and then distributes the tasks (building blocks) to all the available nodes/cores. 
- What about software that requires a license to run - wouldn't biobb require the license then as well? 
  > biobb wraps the software, the software installation is independent of that 
- How about the general performance? Is there any loss/gains in computational cost, speed, when workflows are executed using BIOBB versus let's say a bash script and gmxapi? For example, read/write, communication times and so on. 
  > We have never measured that, but it shouldn't be much loss. And when coupled to managers such as PyCOMPSs, you have seen the efficiency in terms of CPU usage and parallelization. The time needed to produce a result can be greatly reduced just using a higher number of cores (in a run having independent tasks).
- Should all steps be consecutive, or we can write a pipeline with parallel/async simulation? (eg processing subunits of protein complex in parallel and then combine in nex simulations) 
  > With basic command line BioBB workflows, it can be done with Python logic. With PyCOMPSs coupled BioBB workflows, there's again PyCOMPSs utilities to control that, such as [*Wait-ons*](https://compss-doc.readthedocs.io/en/stable/Sections/02_App_Development/02_Python/01_Programming_model.html?highlight=wait_on#synchronization) functionalities. 
- In the introduction you mentioned docking with HADDOCK and Autodock. Are they currently implemented with the biobb? 
  > BioBB has now AutoDockVina integrated, see the [biobb_vs](https://biobb-vs.readthedocs.io/en/latest/) module. We are thinking about integrating AutoDock4.0 and Glide, even though this last one could not be shared with conda packages (Schrödinger license).
  > HADDOCK team is working on having a modularized version, without license issues (CNS) that will be integrated in the BioBB. Plan is to have it by the end of 2021. 
- Can you ran biobb in steps, so that you are confident at each step the output is okay?
  > Yes, you can use the Jupyter Notebooks for that, and execute cell by cell, inspecting the logs and intermediate results.

## Python API

:::info
For showcasing the python API we need:
 - The brand new GROMACS2021
 - It's librarires so python can talk directly to it
 - thread-MPI enabled GROMACS2021
 - MPI
 - and the newest gmxapi Python package

As this is complex installation procedure, we provide a "singularity" image, where we have everything installed for you on Puhti - to fire up the installed software on Puhti and set up a connection so that you can see directly in your browser what happens on Puhti, follow the instructions below.

The alternative is for you to install everything locally on your machine yourself - something we would like to encourage if you plan to use gmxapi functionality later yourself.

To mitigate download delays, please `docker pull gmxapi/tutorial` as soon as possible. Docker images are distributed in layers, so if there are updates before the workshop session, it will take much less time to synchronize with another `docker pull` later than to do the full download.

*Last update: 11:17am CET, 2 February*
:::

:::warning
If you pulled the Docker image before 5:37pm CET, the next image update will not be small. Please pull again soon, if you can.
:::

### Accessing workshop content

#### Option 1: Install locally

0. Set up whatever style of Python virtual environment you like.
1. Install GROMACS 2021 and the gmxapi Python package: [Instructions](https://manual.gromacs.org/current/gmxapi/userguide/install.html)
2. Get the workshop content archive. Visit the following Google Drive link to get [gmxapi-introduction.tgz](https://drive.google.com/file/d/1zhERf8OI_Zr5AbyofNUnczqgDdvc8j_u/view?usp=sharing)
3. Put the archive somewhere you want it. Then,
    ```
    tar xvf gmxapi-introduction.tgz
    cd gmxapi-introduction
    ```
3. Install additional Python requirements for the workshop:
    ```pip install -r requirements.txt``` 
4. Run `jupyter notebook` and open the indicated local URL.

Note: The archive was initially incomplete. Please update the local copy of the content before the workshop session if downloaded before the *last update* time given above.

#### Option 2: Docker container

1. `docker pull gmxapi/tutorial`
2. Assuming port 8888 is available locally,
    `docker run --rm -ti -p 8888:8888 gmxapi/tutorial`
3. Open the indicated local URL.

Note that the `--rm` guarantees that abandoned containers don't accidentally fill up your hard drive, but also that local changes will be lost when you stop the container.

Consider saving notebooks through the web interface, or refer to Docker documentation for how to take snapshots, if needed.

#### Option 3: Tunneling to the Singularity container

```sequence
Your Computer->Puhti: ssh trainingXXX@puhti.csc.fi
Note over Puhti: Start singularity image\n Read output
Puhti->Your Computer: ssh tunnel command\nbrowser address
Your Computer->Your Computer: Start new terminal
Note over Your Computer: type ssh tunnel command
Your Computer->Your Computer: Open browser
Note over Your Computer: browser address\nopen jupyter notebook\n run tutorial
```

### Singularity tips

#### Watch how to do this on youtube

https://www.youtube.com/watch?v=Q2w0ACywLdY

Open connection to Puhti, set up environment:
#### Start a singularity image
```bash
ssh trainingXXX@puhti.csc.fi

wget https://a3s.fi/Gromacs_utilities/gromacs_2021.tar.gz
tar -xavf gromacs_2021.tar.gz 
cd gromacs_2021

curl -L -o gmxapi-introduction.tgz "https://drive.google.com/uc?export=download&id=1zhERf8OI_Zr5AbyofNUnczqgDdvc8j_u"
tar xvf gmxapi-introduction.tgz
```
Set up an interactive batch job and launch the container:
```bash
sinteractive -c 1 -m 4G -d 250
singularity run -B /users/$USER gromacs2021-notebook-puhti.sif
```

This will print out two options on how to tunnel the connection to your local machine AND commands how to start the notebook in your browser. Both differ, whether you've set up your ssh keys for the connection or not. Leave this terminal open.

#### Start ssh tunnel

Open a new local terminal.

You need a unique port for your connection. To achieve this copy from the output of the last command above.
:::warning
The command to copy should look *similar* to `ssh -L 5010:localhost:5010  training010@puhti.csc.fi ssh -L 5010:localhost:8888 training010@r07c51.bullx`
:::

#### Open notebook in your browser

Open your local browser and type in the address field the output from the `singularity` command above.

:::warning
The command is *similar* to `http://localhost:5010/?token=29fe5bdd3b3116ceae444fc16ace92e875281229801356a0`
:::

### Follow up and additional information

* [GROMACS manual](https://manual.gromacs.org/current/gmxapi/index.html)
* [Slack invite](https://join.slack.com/t/gmxapi/shared_invite/zt-loj2mehh-ONI2EmU4yxjOik3~L0ucbw)
* [GitLab issue tracker](https://gitlab.com/gromacs/gromacs/-/issues)
* Email [Eric](mailto:ericirrgang@gmail.com)
* [DOI: 10.1093/bioinformatics/bty484](https://doi.org/10.1093/bioinformatics/bty484)
* [Bioexcel webinar](https://bioexcel.eu/webinar-molecular-simulation-control-gmxapi-2018-09-19/) for [gmxapi 0.0](https://github.com/kassonlab/gmxapi/tree/release-0_0_7)

### Q&A

- How would one benefit of using gmxapi? How is it different / better than the biobb we were just introduced? Both of them are designed for building and running gromacs workflows using Python syntax and scripts?
  > gmxapi let's you modify more GROMACS related things, when using biobb you will have have a building block that is doing exactly what you want. `biobb` is great at connecting different software, `gmxapi` helps you to do things with GROMACS onlys
- gmxapi cannot handle POSIX Path objects? Or I do something wrong? `em = gmx.read_tpr(Path("usage/em.tpr"))` raises an error 
  > Indeed, that is something we work on; for now use strings.
- can we use BytesIO or something like this instead of normal files in filesystem?
> 1. gmxapi sample software illustrates using the Python buffer protocol for passing data between components or software layers.
> 2. The gmxapi data model requires additional work that we had hoped to coordinate with the GROMACS dev team. It seems clear that we need to be able to represent opaque objects generally, in addition to just array buffers and function pointers. Hopefully we'll see a general solution emerging for gmxapi 0.3.
> 3. In the case of simulation input, specifically, there is a new C++ abstraction that we will be developing this year, so expect a much more useful and performant SimulationInput moving forward.
- What about the off precision, of `.mdp` file values (0.01 shows up as as 0.0099999992339)
  > What the python api shows is what is actually used - the 32 bit binary representation of 0.01 is actually the one shown by gmxapi.
- Will missing parameters be set by default values?
> For the example shown (we were editing a TPR file) the simulation input was fully specified by grompp. We only _modified_ existing values with *modify_input*. Preexisting values were simply copied from the source to the destination.
- Could you provide reading material about «Future» concept in general?
> In the Python context, compare the semantics of the [concurrency module](https://docs.python.org/3/library/concurrent.futures.html), the [asyncio module](https://docs.python.org/3/library/asyncio-future.html), and [Parsl](https://parsl.readthedocs.io/en/stable/userguide/overview.html#futures). Also compare these with C++ [std::future](https://en.cppreference.com/w/cpp/thread/future). See also [Wikipedia](https://en.wikipedia.org/wiki/Futures_and_promises). 
- Does Gromacs have a C++ API? Or should we patch its source code to add plugins? 
> The emerging low-level interface for developing against GROMACS is the [MDModules](https://manual.gromacs.org/current/doxygen/html-lib/classgmx_1_1MDModules.xhtml) set of interfaces, but this generally still requires patching GROMACS source. For an example of run-time (dynamic) extension of a subset of IForceProvider (a part of the MDModules framework), see the [Restraint headers](https://manual.gromacs.org/current/doxygen/html-lib/group__module__restraint.xhtml) and the [sample restraint](https://gitlab.com/gromacs/gromacs/-/tree/master/python_packaging/sample_restraint).
> 
## Participant flash talks

- Slide(s) shown by organizers, narration by you
- Strict maximum 3 minutes
- Who you are, your background, current projects or interests, collaboration opportunities, ...


## How to share files with Atte

```bash
module load allas
allas-conf
a-publish -b bucket-name yourfile.tgz
```

# Feedback
> Just wanted to say that I found exactly what I expected from the workshop: cool ways to tame multiple Gromacs simulations. Thank you so much. It also would be interesting to learn about Gromacs—Plumed workflows and ways of efficient automatization of trajectory analysis. [name=Danila Iakovlev]
