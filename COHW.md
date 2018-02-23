<!-- $theme: gaia -->
<!-- template: gaia -->
<!-- $size: 4:3 -->
## Integrated Analysis of Data from Automated Instruments

#### A case study in repurposing modern "DevOps" tools for real-time science
<br>

###### Vaughn Iverson¹ ², Chris Berthiaume¹, Francois Ribalet¹, Ginger Armbrust¹

University of Washington
<small>
¹ School of Oceanography
² eScience Institute
</small>

---
<!-- page_number: true -->
# A bit about me...

<div style="text-align:center"><img width=60% src="metagenome.gif"/></div>

---
# ...and our lab

<div style="text-align:center"><img width=85% src="labretreat_2015.jpg"/></div>

---
# SeaFlow: <span style="font-size:22pt">*"A census for the very small"*</span>
##### 

<div style="text-align:center"><img width=85% src="seaflow_paper.png"/></div>
<br/>
<img width=51% align=left src="seaflow_diagram.jpg"/>
<img width=40% align=right src="seaflow_installed.jpg"/>

---
## Realtime Integrated Monitoring

<div style="text-align:center"><img width=90% src="seaflowviz.png"/></div>

[http://armbrustlab.github.io/seaflowviz3](http://armbrustlab.github.io/seaflowviz3)

---
# Gradients Cruise
<div style="text-align:center"><img width=50% src="simons.png"/></div>
<div style="text-align:center"><img width=70% src="main-image1.jpg"/></div>

---
# Gradients Cruise
<img width=70% align=right style="transform: rotate(180deg)" src="instruments.jpg"/>

#### Now with 
## MOAR 
#### automated
#### instruments!

---
# Gradients 2.0

Integrate all the things!
**IT** will be Great!  Build **IT**!

---
# Gradients 2.0

==Integrate all the things!
**IT** will be Great!  Build **IT**!==

*Uh, what is "IT" exactly, again?*

---
# Gradients 2.0

==Integrate all the things!
**IT** will be Great!  Build **IT**!==

==*Uh, what is "IT" exactly, again?*==

Oh, you know, that great thing you did for SeaFlow...
... but with **MOAR** Instruments!
Shouldn't be too hard, right? When will **IT** be done?

---
# Gradients 2.0

==Integrate all the things!
**IT** will be Great!  Build **IT**!==

==*Uh, what is "IT" exactly, again?*==

==Oh, you know, that great thing you did for SeaFlow...
... but with **MOAR** Instruments!
Shouldn't be too hard, right? When will **IT** be done?==

*Um... No. That's not how this works.* 
*We're going to need agree on the requirements first.*

---
# Gradients 2.0

==Integrate all the things!
**IT** will be Great!  Build **IT**!==

==*Uh, what is "IT" exactly, again?*==

==Oh, you know, that great thing you did for SeaFlow...
... but with **MOAR** Instruments!
Shouldn't be too hard, right? When will **IT** be done?==

==*Um... No. That's not how this works.* 
*We're going to need agree on the requirements first.*==

Huh? How do we do that?

---
### Gradients 2.0 Requirements Summarized:
* Capture as much data as possible, as it's generated
    * From both instruments and experiental results 
* Enable simple, realtime interactive plotting
    * Customizable on the fly by scientists
* Tolerate certain hardware and network failures
    * Within defined limits  
* Same capabilities available on ship and shore
    * But, lower resolution data on shore 

---
# DevOps

<div style="text-align:center"><img style="background-color:white; border:2vw solid white" width=55% src="Devops.svg"/></div>

---
# DevOps

<div style="text-align:center"><img style="background-color:white; border:2vw solid white" width=80% src="Devops-toolchain.svg"/></div>

---
# DevOps

<div style="text-align:center"><img style="background-color:white; border:2vw solid white" width=90% src="Devops-toolchain-annotated.svg"/></div>

---
# SciOps? <span style="font-size:14pt">*(not PsyOps!)*</span>

### Or perhaps: *ResearchOps*

---
# Monitoring tools

<div style="text-align:center"><img style="background-color:white; border:2vw solid white" width=30% src="monitoring.svg"/></div>

Popular "stacks" of OSS monitoring tools:
* "**ELK**": **E**lasticsearch, **L**ogstash, **K**ibana
* "**TICK**": **T**elegraf, **I**nfluxDB, **C**hronograf, **K**apacitor

Also popular: Promethius, Grafana 

---
# What are all of these things?

<div style="text-align:center"><img style="background-color:white; border:2vw solid white" width=70% src="Tick-Stack-Complete.png"/></div>
<small>influxdata.com</small>

---

##### Architecture

<div style="text-align:center"><img style="background-color:white; border:2vw solid white" width=85% src="architecture.svg"/></div>


---

# Consul / Nomad

---

# Minio

---

# Restic

---

# Custom Upload

---

# InfluxDB

---

# Grafana

---

# Lessons / Takeaways

## Time

## Rsync

## Maps

---

# Conclusion

