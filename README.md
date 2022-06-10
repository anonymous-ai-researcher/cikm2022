# README
## 【Update】the script of analyzing the connection between timeout and maxDepth

* The files OxfordAnalyse.txt and BioPortalAnalyse.txt are the meta data. Run the script main.py and get the result of the Table 3 in our paper.
## Welcome
* Welcome to this site and thanks for your interest in trying out our uniform interpolation (UI) tool and logical difference (UI-Diff) tool. Both tools are implemented in Java using the **OWL API**, so to get them work, first make sure you have JDK/JRE installed on your machine.
* Your feedbacks are always welcome!

## Semantic difference between SNOMED CT ontologies

* ![image](https://github.com/anonymous-ai-researcher/lics2022/blob/master/information_gain_and_loss.jpg)

## GUI

* We would also like to invite the reviewers/users to try out user-friendly web access to these tools via [here](http://www.forgettingshow.info).

## Environment requirement

* JDK 1.8
* IDE: IDEA 
* Maven

## Data

* All the test data, including Oxford-ISG snapshot, BioPortal snapshot,  SNOMED CT and GO, can be downloaded at https://github.com/anonymous-ai-researcher/lics2022.
* Statistics of Oxford-ISG & BioPortal (Min:Minimum, Max:Maximum, Med:Medium, 90 Ptl: 90th Percentile):


<div align="center">
<table class="tg">
<thead>
  <tr>
    <th class="tg-7btt" colspan="2">Oxford</th>
    <th class="tg-7btt">Min</th>
    <th class="tg-7btt">Max</th>
    <th class="tg-7btt">Med</th>
    <th class="tg-7btt">Mean</th>
    <th class="tg-7btt">90Ptl</th>
    <th class="tg-7btt">%</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow" rowspan="3">I</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">1582</td>
    <td class="tg-c3ow">86</td>
    <td class="tg-c3ow">191</td>
    <td class="tg-c3ow">545</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">332</td>
    <td class="tg-c3ow">10</td>
    <td class="tg-c3ow">29</td>
    <td class="tg-c3ow">80</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">990</td>
    <td class="tg-c3ow">162</td>
    <td class="tg-c3ow">262</td>
    <td class="tg-c3ow">658</td>
    <td class="tg-c3ow">82.20</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">II</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">200</td>
    <td class="tg-c3ow">5877</td>
    <td class="tg-c3ow">1665</td>
    <td class="tg-c3ow">1769</td>
    <td class="tg-c3ow">2801</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">887</td>
    <td class="tg-c3ow">11</td>
    <td class="tg-c3ow">34</td>
    <td class="tg-c3ow">61</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">1008</td>
    <td class="tg-c3ow">4976</td>
    <td class="tg-c3ow">2282</td>
    <td class="tg-c3ow">2416</td>
    <td class="tg-c3ow">3937</td>
    <td class="tg-c3ow">89.70</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">III</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">1162</td>
    <td class="tg-c3ow">9809</td>
    <td class="tg-c3ow">4042</td>
    <td class="tg-c3ow">5067</td>
    <td class="tg-c3ow">8758</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">1</td>
    <td class="tg-c3ow">158</td>
    <td class="tg-c3ow">4</td>
    <td class="tg-c3ow">23</td>
    <td class="tg-c3ow">158</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">5112</td>
    <td class="tg-c3ow">9783</td>
    <td class="tg-c3ow">7277</td>
    <td class="tg-c3ow">7195</td>
    <td class="tg-c3ow">9179</td>
    <td class="tg-c3ow">94.45</td>
  </tr>
  <tr>
    <td class="tg-7btt" colspan="2">BioPortal</td>
    <td class="tg-7btt">Min</td>
    <td class="tg-7btt">Max</td>
    <td class="tg-7btt">Med</td>
    <td class="tg-7btt">Mean</td>
    <td class="tg-7btt">90Ptl</td>
    <td class="tg-7btt">%</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">I</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">784</td>
    <td class="tg-c3ow">127</td>
    <td class="tg-c3ow">192</td>
    <td class="tg-c3ow">214</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">122</td>
    <td class="tg-c3ow">5</td>
    <td class="tg-c3ow">15</td>
    <td class="tg-c3ow">17</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">982</td>
    <td class="tg-c3ow">283</td>
    <td class="tg-c3ow">312</td>
    <td class="tg-c3ow">346</td>
    <td class="tg-c3ow">96.89</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">II</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">5</td>
    <td class="tg-c3ow">4530</td>
    <td class="tg-c3ow">1185</td>
    <td class="tg-c3ow">1459</td>
    <td class="tg-c3ow">1591</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">131</td>
    <td class="tg-c3ow">12</td>
    <td class="tg-c3ow">30</td>
    <td class="tg-c3ow">33</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">1023</td>
    <td class="tg-c3ow">4977</td>
    <td class="tg-c3ow">2401</td>
    <td class="tg-c3ow">2619</td>
    <td class="tg-c3ow">2782</td>
    <td class="tg-c3ow">97.18</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">III</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">432</td>
    <td class="tg-c3ow">8340</td>
    <td class="tg-c3ow">4363</td>
    <td class="tg-c3ow">4387</td>
    <td class="tg-c3ow">4806</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">135</td>
    <td class="tg-c3ow">17</td>
    <td class="tg-c3ow">30</td>
    <td class="tg-c3ow">34</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">5084</td>
    <td class="tg-c3ow">8836</td>
    <td class="tg-c3ow">6934</td>
    <td class="tg-c3ow">6912</td>
    <td class="tg-c3ow">7109</td>
    <td class="tg-c3ow">98.72</td>
  </tr>
</tbody>
</table>
</div>

## Import of this project

* Unzip this project.
* Import it into IDEA.
* Make the src folder as source root.
* Make sure that the jar package under the root folder has been added into project as libriaries.

## Description of the UI tool

* The UI tool is a high-performance prototype for computing uniform interpolants of **ELH-Ontologies**. It can be used as a Java library or a standalone tool for UI and related tasks.

* A uniform interpolant is a restricted view of an ontology that uses only a sub-signature of the ontology, namely, the interpolation signature, while preserving all logical entailments over the interpolation signature. A uniform interpolant can be computed by forgetting the names (usually incrementally) not  in the interpolation signature (the set of the names to be forgotten is called the forgetting signature) in such a way that all logical entailments are preserved up to the remaining signature, which amounts to the interpolation signature.

* Our UI tool can always compute a uniform interpolant for ELH-Ontologies. If an input ontology is not an ELH one, our tool simply takes the ELH fragment of the ontology and discards those axioms not expressible in ELH. If an input ontology contains cyclic dependencies over the names in the forgetting signature, the result cannot always be represented finitely without fixpoint operators. Since fixpoint operators are not supported by OWL API, our UI tool introduces additional concept names, namely definers, to the output ontology that simulate the behaviour of fixpoint operators. In this sense, the result is no longer a uniform interpolant, since it contains extra names that are not in the specified interpolation signature.

## Run of the UI tool

* To run the forgetting method, go to  **/src/forgetting/Forgetter.class** and call the method: 

  ```java
  public Set<OWLAxiom> ForgettingAPI(Set<OWLObjectProperty> roles, Set<OWLClass> concepts, OWLOntology onto)
  ```

* The input are a set of role names to be forgotten  ( ``` Set<OWLObjectProperty> roles ``` ),  a set of concept names to be forgotten ( ``` Set<OWLClass> concepts ``` ) and an ELH-Ontologies from which the concept and role names are forgotten ( ``` OWLOntology onto ``` ).

* The output is another ELH-Ontology which is a Σ-uniform interpolant of the ontology ``onto``, represented as a set of OWLAxioms.

* An example illustrating the usage of the UI tool is included in the Forgetter.class main function.

## Description of the UI-Diff tool

* The UI-Diff tool is a high-performance prototype for computing a finite representation of the logical difference **UI-Diff(O1, O2)** between two ELH-Ontologies O1 and O2. The tool implements a two-step algorithm with the **first step** computing a Σ-uniform interpolant V2 of O2 for Σ = sig(O1) ∩ sig(O2) using the UI tool, and the **second step** computing the UI-witness set W2 by collecting all axioms α ∈ V2 with O1 ⊭ α using the DL reasoner HermiT.

* As a third step, it may be useful to partition the UI-witnesses into explicit and implicit UI-witnesses. An explicit UI-witness is the one that is originally contained in O2. An implicit UI-witness is the one that is originally not contained in O2, but entailed by O2. Implicit UI-witnesses are generated by uniform interpolation.

* UI-Diff(O1, O2) computes the information gain from O1 to O2, or information loss from O2 to O1. So if one wants to compute the information gain from O2 to O1 (information loss from O1 to O2), just swap the places of O1 and O2, i.e., **UI-Diff(O2, O1)**.

## Run of the UI-Diff tool

* To run the UI-Diff method, go to **/src/forgetting/LDiff.class**, and call the method:

  ```java
  public void compute_LDiff(OWLOntology onto_1, OWLOntology onto_2, String path)
  ```

* The input are two ELH-Ontologies O1 ( ```onto_1``` ), O2 ( ```onto_2``` )  and a ```path``` specifying the location where you want the output to be locally saved.

* The output are a set of UI-witnesses, a set of explicit UI-witnesses and a set of implicit UI-witnesses, all represented as .owl files. 
* An example illustrating the usage of the UI-Diff tool is included in the LDiff.class main function.

