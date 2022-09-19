---
name: 'Debugging of BPMN Processes using Coloration Techniques'
speakers:
  - Quentin Nivon
  - Gwen Salaün
categories:
  - Modelling & Verification
---

A business process is a collection of related tasks organized in a specific order 
whose overall execution solves a specific service or product. BPMN has become 
the standard workflow-based notation for developing business processes. 
Designing business processes using BPMN is however error-prone. Recent works have proposed verification techniques for analyzing processes and for detecting possible issues. In particular, model checking is an established technique for automatically verifying that a model (e.g., a BPMN process) satisfies a given temporal property. When the model violates the property, the model checker returns a counterexample, which is a sequence of actions leading to a state where the property is not 
satisfied. Understanding this counterexample for debugging the process is not 
an easy task, especially if the counterexample is not expressed using the 
original notation (BPMN here). In this paper, we focus on the model checking of 
BPMN processes. When properties are violated, we propose to transform counterexamples back on to the original BPMN process in order to simplify the debugging steps. To do so, we rely on coloration techniques. The approach proposed in this paper is fully automated using several tools and was validated on many examples. 