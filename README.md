# PEMEC-ThesisProject

twoPhaseEulerIsothermal is the standard twoPhaseEulerFoam, but with the energy equation excluded.

porousV3  is the twoPhaseEulerFoam solver with enchanced two-phase porous treatment - requires inclusion of constant/porousProperties

porousHeatTransferV0 is porousV3 including the total energy equation, modified for the inclusion of a porous layer.

The folder gridConv contains the simulations used for a grid convergence study.

The modelStudy contains a permeability study and a flow regime study.
