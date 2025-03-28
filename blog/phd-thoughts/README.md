# PhD thoughts

## Tuesday, September 24, 2024
How is my Ph.D. going?
When you are at school and all your classmates get As and Bs in the exam, and you get a C - you still pass, but are clearly worse than average.
But the teacher is still encouraging, so you still enjoy the class.

That's basically how I'm feeling.

## Monday, February 24, 2025
I started my Ph.D. in May 2022. There have been many angles of thought I have been pursuing. In the last 2 years, one of my main activities has been to understand the local existence proof for classical solutions of Vlasov-Poisson in more detail. I mainly use [this](https://doi.org/10.1016/S1874-5717(07)80008-9) reference. My aim, which I am working towards, is to extend the proof by allowing initial values from the space of continuously differentiable L1-L-infinity functions. What I have already accomplished is removing the requirement that the initial value needs to be non-negative: Everything works just fine even when the initial value function is allowed negative values.

Because of becoming a father and the challenges which are part and parcel of it, during the months October 2024 up until today, I have been able to do as good as no work. Today is the first day where I have actually effectively worked.

## Friday, March 28, 2025
Basically, my current idea is to use the topological dual E' of the space E of smooth (real-valued) functions on R^2d (with d=3 probably) as configuration space for Vlasov-Poisson, and also N-Body problem. The fact is that E has a Lie algebra structure given by the standard Poisson bracket on R^2d, and this Lie algebra structure on E induces a Poisson bracket / Poisson structure on E'. 

The fact that this works has been also studied and stated in [this](https://www.cambridge.org/core/journals/forum-of-mathematics-sigma/article/rigorous-derivation-of-the-hamiltonian-structure-for-the-vlasov-equation/F8603D4224762764E7C83B4042457750?utm_campaign=shareaholic&utm_medium=copy_link&utm_source=bookmark) source, and they also go on to describe Vlasov-Poisson as the Hamiltonian flow of a Hamiltonian vector field, which is defined using the Poisson bracket on E' and a fitting energy functional H_{Vl} on E'. I have to look into this more to check that what they did there is actually legit. Also, they didn't really think it through in depth: Did they think about what initial values are allowed? Any point in E'? But the points in E' can be continuous Radon measures, Dirac delta peaks, or (the most general description) sums of derivatives of Radon measures. They didn't think about whether all these initial values are admissible, and what they mean. (Or did they? Quite a dense paper.) They didn't also think about existence of flow questions.

I was also for long time (because of something my advisor said) concerned with the fact that the configuration space shouldn't have too many weird objects. By the way, E' is called the space of compactly supported distributions. But only recently realized that this doesn't have *that many* unusual objects. I have decided to work with this, in any case.

One thing I have definitely got out of this PhD so far is the joy of learning about topological vector spaces. My main source for this is the book "Topological vector spaces, Distributions and Kernels" by Francois Treves. [ToC](https://web.icmc.usp.br/SCATUSU/Boletim_aquisicao/Boletim_Janeiro_2016/Capas_Janeiro_2016/BIBLIOTECA_158_Treves_Topological0001.pdf) [Book](https://rexresearch1.com/TopologyLibrary/TopologicalVectorSpacesTreves.pdf)

I am at the moment writing up the whole theory part (just a rough draft), and will upload it here when I am done.
I have also been told (quite early on in my PhD) that while developing all this theory and neat description is a nice idea, there needs to be some merit of going through the whole process to justify it and also have a result for a PhD where people will say "Ah, that's why it is interesting!" Just theoretical description for its own sake is not necessarily enough. 

I've got some ideas as to how I could exploit the theory (which I will have described in a few weeks) to get some interesting results. By the way, what constitutes an "interesting" result is very different depending on who is looking. I might find something interesting for Geometry people, for PDE people, for Numerics people. Who knows. Only the future will tell.
