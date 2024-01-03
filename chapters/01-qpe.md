# Why Quantitative Population Ethology?

Since the advent of theoretical population biology, there have been a
number of attempts to simulate and predict the states of various
biological systems using any number of sophisticated analytical,
statistical, and numerical techniques. In some cases such techniques
have been extremely successful, while in other applications the same
approaches have failed miserably. We shall briefly discuss some of the
general properties of theoretical population biology and then examine
two biological systems as they might be viewed by a field biologist.
From this study we conjecture some of the properties that an individual
in a small population may exhibit. Based on these properties we suggest
a possible modeling technique that is uniquely dependent on the
information that the biologist observes.

Knowledge about animal behavior comes from two intrinsically different
types of research. Ethology involves extensive examination of the
physical and behavioral properties of an individual and its relationship
to other members of its community. At the other end of the spectrum,
population biology studies the general characteristics and dynamics of
whole communities. We propose to combine these as quantitative
population ethology, modeling the population structure by accounting for
the dynamics and behavior of each individual within that population.
This approach is quantitative in two senses: it can be based on field
measurements, and it can summarize information over time and over
populations of individuals. In this paper we examine some model
requirements for simulating the properties and dynamics of populations
through events that occur to individuals.

An ethologist’s description of individual behavior builds quantitative
and qualitative data into an intriguing mosaic. Each member of a
community responds to its unique history, environment, health and social
position, possibly affecting the success or failure of other segments of
that community. Important facets of an individual’s behavior, such as
predator search patterns, prey evasion tactics and protective
coloration, can shift the balance between species. Reduced reproductive
success by a dominant male may threaten the survival of a local
population. Limited adaptability of a group of individuals in a changing
environment may threaten an entire population.

The major problem with using properties of individuals to describe an
entire biological system is that individuals respond uniquely to stimuli
in ways not easily characterized by \`density response’ summaries. In
addition, modeling a population of individuals, unless done judiciously,
ultimately leads to substantial dimensionality problems. The complex
operational properties of an individual preclude elegant analytic
solutions at the population level. On the other hand, simulations that
closely mimic individual behavior tend to be weak in mathematical
structure and computationally intractable. How can we establish
simulations having a balance of attention to biological details and
sufficient mathematical structure to yield meaningful results?

## Maleable Tools for the Field Biologists

The primary focus of modeling is the
\``information'' that is derived from examining attributes and their relationship to acceptance, and not the specific`best’
model selected. It is important for the researcher to not be distracted
from that objective in the pursuit to develop a \`best’ model. Modeling
results should report the information as a clear set of recommendations
for product improvement, and not focus on any specific mathematical
model or function.

During model development several valid models should and will be
identified, a result potentially offering convergent learning and
convergent validation of important attributes. Convergent learning is
the basis for identifying important
`guideline' variables not represented in the selected`best’ model.
Convergent validation is useful for providing low risk product
development direction. Where different models provide contradictory
information, the researcher uses statistical, practical and experiential
criteria to resolve the conflict.

### Tying simulations to field data

## Simulating Millions of Organisms

### Limitations of brute force computing

keep simulation growth linear in number of individuals, complexity of
behavior

### Loose coupling of model cascades

span and resolution

## From Individual Behavior to Evolution

## Discussion from QPE

The researcher interested in exploring the structure and dynamics of a
population is faced with an extremely difficult problem of connecting
classical modeling techniques to realistic biological processes. Serious
problems arise in any brute force, component process approach.

The fundamental problem in an event-driven approach is how to
interconnect relationships after an event has occurred. Any a priori
approach would grow a model beyond bounds of computing time and
complexity. The way that time is handled is crucial. While the
biological system comprised of individuals is parallel in time, the
event-driven model structure is sequential, with each new event
modifying a complex hierarchical structure. This transfers attention
from an explicit, static representation of the state-space to a dynamic,
implicit one, with events driving time asynchronously. This
transformation yields efficient computations while allowing complex
interactions to be decomposed into coupled events. Future events are
quasi-independent given the current state of the biological system. This
allows us to focus on the next scheduled future event and have the model
simulation reassemble itself after that event is processed.

If we analyze the structure and dynamics of a population at the
individual level, the researcher faces an inherently probabilistic
simulation that is complex and may be operationally intractable, with
the following properties:

The inherently probabilistic structure at this level of description is
central. The biological structure emerges over many individual events.
The high dimensionality of the biological system forces the researcher
to sample individuals and events. Any description is necessarily
incomplete and stochastic.

In view of this inherent complexity, prediction of the future state of
given individuals, or groups of individuals, is laced with uncertainty.
Predictions on global properties tend to concern aspects that are not
directly measurable, and hence cannot be validated.

Implicit in our modeling approach is the philosophy that any
mathematical or numerical technique should not dictate the biology, but
instead should mimic the biological process as much as possible. Our
event-driven quantitative population ethology does not dictate how that
process is done. We suggest that the actual simulation be driven by how
the biologist perceives the system and chooses to structure the
simulation around key research questions.

We propose the concept of quantitative population ethology modeling as
an alternative to traditional population ecology models. This provides
both a practical model approach as well as a philosophy that gives the
field biologist tools and a perspective to analyze processes and
structure observed in the field. Simulations can be designed to mimic
the perceived structure and dynamics observed in the field. In addition,
the approach suggested here has the potential of providing a tool for
analyzing emerging properties of self-organizing systems (Kauffman
1993,1995; Paczuski and Bak, 1999; Paczuski et al. 1995).
