# **6. Emerging Challenges in Modern Power Systems for Inter-Area Oscillation** 

The rapid transition toward low-inertia power systems with high penetration
of converter-interfaced renewable sources has changed the characteristics of
inter-area oscillations. Replacing part of the synchronous generation with
these resources does not change the fundamental definition of these modes;
rather, it affects their dynamic properties, such as modal frequency, damping
ratio, and mode shape. In this context, inter-area oscillation studies are no
longer limited to the analysis of synchronous generators alone, but also
include the impact of converter-interfaced resources, changing operating
conditions, and control and diagnostic challenges. Accordingly, this chapter
discusses the main emerging issues that are reshaping the analysis and damping
of inter-area oscillations in modern power systems [C1]–[C8].

**6.1 Impact of Converter-Interfaced Renewable Penetration and
Inertia Redistribution on Inter-Area Modes**

Assessing the impact of converter-interfaced renewable resources on
inter-area oscillations has become more complex than simply relating it to
penetration level. A study on high photovoltaic penetration in the U.S. Eastern
Interconnection showed that increasing photovoltaic generation led to an
increase in the frequency of the dominant inter-area mode and a reduction in
its damping ratio. The same study also showed that photovoltaic plant control
settings can alter the mode shape or introduce new modes associated with
converter-control dynamics [C1].

In another study on the U.S. Eastern Interconnection under high wind
penetration conditions, the results showed that damping can improve under
certain operating conditions, while the oscillation frequency increases due to
the reduction in equivalent system inertia [C2]. This indicates that the
difference between the reported photovoltaic and wind results is not attributed
to the renewable resource type alone, but also to the control strategy,
resource location, changes in power-flow patterns, and the synchronous
generators being displaced. Therefore, a more accurate interpretation is that
converter-interfaced renewable resources tend to increase the frequency of some
inter-area modes due to reduced equivalent inertia, whereas their impact on
damping remains dependent on system and control-specific factors.

Studies related to system inertia further support this distinction between
modal frequency and damping. A measurement-based study of the Nordic power
system showed that the frequency of the dominant Finland–Sweden inter-area mode
is strongly correlated with the system inertia level, whereas the damping of
the mode shows no clear direct correlation with inertia [C3]. This indicates
that reduced inertia may explain the shift in modal frequency, but it is not
sufficient by itself to explain changes in the damping ratio.

In addition, inertia distribution and the location of converter-interfaced
resources have a significant influence on inter-area modal properties. Some
studies have shown that placing damping or inertia-emulation resources in
low-inertia areas, or farther from the center of inertia, can enhance the
damping of inter-area modes [C4]. A recent study on large-scale power systems
also showed that modal properties are affected by the location of the displaced
synchronous generator or the added inverter-based resource. Moreover, tuning
control parameters, such as the active power–frequency droop coefficient and
the active-power measurement low-pass filter time constant, can mitigate some
of these changes [C5]. Hence, the location and tuning of converter-interfaced
resources affect not only modal frequency and damping, but may also reshape the
mode shape, thereby influencing coherent group identification, measurement
placement, and damping-controller location.

Accordingly, the main challenge in modern power systems is not merely the
increase in renewable penetration, but rather how the spatial replacement of
synchronous generators, inertia redistribution, converter-control parameters,
and operating conditions jointly affect inter-area modal properties. Future
stability studies should therefore move beyond general penetration-based
assessments toward more detailed modal evaluations that account for resource
location, modal participation, mode shape, and converter-control dynamics.

**6.2
Converter-Based Resources: Damping Support or a Source of New Oscillatory
Interactions?**

Converter-based resources are no longer treated only as replacements for
synchronous generation; they have become active contributors to the modal
behavior of modern power systems. Grid-forming converters and virtual
synchronous generators are designed to emulate selected characteristics of
synchronous machines, such as inertia, damping, and voltage and frequency
regulation. However, recent studies indicate that, although these resources can
emulate some synchronous-machine characteristics, they do not fully reproduce
synchronous-machine dynamic behavior. Their response depends on the control
structure, controller parameters, and interaction with grid operating
conditions [C6], [C7].

Studies on virtual synchronous generators have shown that their
contribution to inter-area oscillation damping depends strongly on the tuning
of the active-power control loop, particularly the damping coefficient. Proper
tuning can improve damping, whereas inappropriate tuning may degrade system
stability [C6]. Other studies indicate that the dynamic differences between
virtual synchronous generators and conventional synchronous generators are
related to converter-control dynamics, such as virtual impedance and
active-power control loops [C7]. Therefore, representing these resources simply
as synchronous machines with modified inertia and damping may not be sufficient
for inter-area oscillation studies.

Converter-interfaced renewable resources can also contribute to oscillation
damping when supplementary control functions are added. Studies on
utility-scale photovoltaic plants have shown that the dynamic response can be
improved through active-power modulation or reactive-current injection using
local measurements at the point of interconnection [C8]. Similarly, studies on
doubly fed induction generator-based wind plants have shown that active- and
reactive-power modulation through converter control loops can improve
inter-area oscillation damping [C9]. However, the effectiveness of these
approaches remains dependent on the resource location, modal observability at
the connection point, available control margin, and operating conditions.

In addition, converter-rich systems introduce an important diagnostic
challenge, since not all observed low-frequency oscillations are necessarily
natural inter-area modes. Some oscillations may result from forced
disturbances, controller malfunctions, or control interactions within
converter-interfaced resources. If the frequency of these oscillations is close
to that of a poorly damped electromechanical mode, the observed response may
resemble an inter-area oscillation [C10], [C11].

For this reason, in modern power systems, it is not sufficient to design
additional damping controllers without first diagnosing the nature of the
observed oscillation. If the oscillation is associated with a natural
inter-area mode, improving damping is the appropriate mitigation action.
However, if the oscillation is forced, identifying and removing the excitation
source is more effective than attempting to damp it as a natural mode. Thus,
the emerging challenge is not limited to using converter-based resources as
damping devices; it also includes understanding their interactions and
verifying the nature of the oscillatory modes observed in the system.

Accordingly, converter-based resources can be viewed as dual-role elements
in inter-area oscillation studies. They can provide effective damping support
if designed and tuned according to the modal behavior of the system, but they
may also introduce new interactions or oscillatory modes if their parameters
and locations are not properly coordinated. Future studies should therefore
consider resource location, control parameters, modal observability, and the
nature of the observed oscillation before adopting any damping action.

**6.3 Comparative Discussion and Future Research Directions**

Recent literature shows that the
impact of renewable energy sources and converter-interfaced resources on
inter-area oscillations cannot be explained by penetration level alone.
Increasing photovoltaic or wind generation may increase the frequency of some
modes due to the reduction in equivalent system inertia; however, their impact
on damping varies depending on the control strategy, resource location, the
synchronous generators being displaced, and the operating conditions [C1],
[C2]. Measurement-based studies further indicate that system inertia is more
strongly associated with modal frequency than with modal damping [C3], while
other studies emphasize that inertia distribution and the location of damping
resources can be critical factors in improving or degrading damping [C4], [C5].
Therefore, the challenge is not only the reduction of inertia, but also how
modern resources reshape modal characteristics in terms of frequency, damping,
and mode shape.

Accordingly, future studies should
move toward a more integrated modal assessment that considers the location of
converter-interfaced resources, inertia distribution, control parameters, and
mode shape, rather than relying only on penetration level [C4], [C5]. The
design of grid-forming converters and virtual synchronous generators should
also account for their impact on existing electromechanical modes [C6], [C7].
In addition, it is important to distinguish natural inter-area modes from
forced oscillations caused by controller malfunctions or interactions, since
incorrect diagnosis may lead to inappropriate damping actions [C8], [C9].