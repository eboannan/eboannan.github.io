 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;[Publications](#publications)&emsp;&emsp;&emsp;[Codes](#codes)&emsp;&emsp;&emsp;[Python](#python)
 

## About
These pages document my past, present and future research works. I summarize these works with publication/code links where applicable.
You will also find tutorials, writings and musings on various topics on python programming, machine learning, spectroscopy, statistics and probability.

I obtained my PhD in Physical Chemistry from the University of Florida doing research in Laser-induced Breakdown Spectroscopy (LIBS). I investigated the use of molecular species formed during LIBS as an analytical quantification technique.

After my doctorate, I did a one year postdoc at the Optical Science Center for Applied Research in Delaware. Whiles there,  I did work on using machine learning on LIBS spectra for detecting ovarian cancer in mice.

I also did another postdoc at the University of Massachusetts, Lowell on using LIBS together with machine learning for the detection of melanoma cancer and Alzheimers using biological samples. I also did NASA-sponsored researches on; simulating the LIBS process, use of machine learning to preprocess LIBS spectra at scale and automating the fitting of emission lines in LIBS spectra.

I am currently a Senior Algorithms Development Scientist at [Nova Measuring Instruments](https://www.novami.com/) where I develop algorithms for XPS, XRF, SIMS, OCD and other technologies.

## Publications
1. Berlo K., Xia W., Zwillich F., Gibbons E., Gaudiuso R., **Ewusi-Annan E.**, Chiklis G.R., Melikechi N. (2022) [Laser induced breakdown spectroscopy for the rapid detection of SARS-CoV-2 immune response in plasma](https://www.nature.com/articles/s41598-022-05509-z). Sci Rep 12, 1614.

2. **Ewusi-Annan E.**, Melikechi N. (2021) [Unsupervised fitting of emission lines generated from laser-induced breakdown spectroscopy](https://www.sciencedirect.com/science/article/pii/S0584854721000549). Spectrochimica Acta Part B: Atomic Spectroscopy 177, 106109.

3. **Ewusi-Annan E.**, Delapp D.M., Wiens R.C., Melikechi N.(2020) [Automatic preprocessing of laser-induced breakdown spectra using partial least squares regression and feed-forward artificial neural network: Applications to Earth and Mars data](https://www.sciencedirect.com/science/article/pii/S058485472030313X). Spectrochimica Acta Part B: Atomic Spectroscopy 171, 105930.

4. Gaudiuso R., **Ewusi-Annan E.**, Xia W., Melikechi N. (2020) [Diagnosis of Alzheimer's disease using laser-induced breakdown spectroscopy and machine learning](https://www.sciencedirect.com/science/article/pii/S0584854720302329).Spectrochimica acta part B: atomic spectroscopy 171, 105931.

5. Gaudiuso R., **Ewusi-Annan E.**, Melikechi N., Sun X., Liu B., Campesato L.F., Merghoub T (2018) [Using LIBS to diagnose melanoma in biomedical fluids deposited on solid substrates: Limits of direct spectral analysis and capability of machine learning](https://www.sciencedirect.com/science/article/pii/S0584854718301290). Spectrochimica Acta Part B: Atomic Spectroscopy 146, 106-114.

6. **Ewusi-Annan E.**, Surmick D.M., Melikechi N. (2018) [Simulated laser-induced breakdown spectra of graphite and synthetic shergottite glass under Martian conditions](https://www.sciencedirect.com/science/article/pii/S0584854717305736). Spectrochimica Acta Part B: Atomic Spectroscopy 148, 31-43.

7. Omenetto N., Jones W.B., Smith B.W., Guenther T., **Ewusi-Annan E.** (2016) [Feasibility of atomic and molecular laser induced breakdown spectroscopy (LIBS) to in-situ determination of chlorine in concrete](https://rosap.ntl.bts.gov/view/dot/31477). Florida. Dept. of Transportation.

8. Melikechi N.,Markushin Y., Connolly D.C., Lasue J., **Ewusi-Annan E.**, Makrogiannis S., (2016) [Age-specific discrimination of blood plasma samples of healthy and ovarian cancer prone mice using laser-induced breakdown spectroscopy](https://www.sciencedirect.com/science/article/pii/S0584854716301070). Spectrochimica Acta Part B: Atomic Spectroscopy 123, 33-41.

9. Merten J.A., **Ewusi-Annan E.**, Smith B.W., Omenetto N., (2014) [Optimizing gated detection in high-jitter kilohertz powerchip laser-induced breakdown spectroscopy](https://pubs.rsc.org/en/content/articlelanding/2014/ja/c3ja50348h/). Journal of Analytical Atomic Spectrometry 29 (3), 571-577.

10. Motl N.E., **Ewusi-Annan E.** , Sines I.T., Jensen L., Schaak R.E. (2010) [Au−Cu alloy nanoparticles with tunable compositions and plasmonic properties: experimental determination of composition and correlation with theory](https://pubs.acs.org/doi/abs/10.1021/jp107637j/). The Journal of Physical Chemistry C 114 (45), 19263-19269.

11. Morton S.M., **Ewusi-Annan E.** , Jensen L. (2009) [Controlling the non-resonant chemical mechanism of SERS using a molecular photoswitch](https://pubs.rsc.org/en/content/articlelanding/2009/cp/b904745j/). Physical Chemistry Chemical Physics 11 (34), 7424-7429.

## Codes
- Machine learning for processing Earth and Mars LIBS spectra

- Approach for automatic fitting of emission lines in LIBS spectra.

## Python 
### Programming Lingo
1. cohesion
2. coupling
3. technical debt
4. REPL
5. IDE: Integrated Development Environment
6. syntax: grammer rules of a programming language
7. race conditions
8. duck typing: Python concept where objects are judged solely on their behavior.
9. EAFP (Easy to As For Permission than Permission)
10. LBYL (Look Before You Leap)
11. pythonic
12. interfaces
   
   
### Design Principles 
When designinig a class in python, you should be guided by the SOLID principles:
1. <span style="color:red">**S**</span>ingle responsibility
2. <span style="color:red">**O**</span>pen to extension but closed to modification
3. <span style="color:red">**L**</span>iskov substitution
4. <span style="color:red">**I**</span>nterface segregation
5. <span style="color:red">**D**</span>ependency inversion

### Design Patterns
Knowing the design patterns allows you to easily write robust code using time-tested techniques. It also facilitates common-ground collaboration and communications among developers. I will cover the common 23 design patterns summarized by the Gang of Four:

Creational:
1. Factory
2. Abstract Factory
3. Prototype
4. Singleton
6. Builder

Structural:
1. Adapter
2. Bridge
3. Composite
4. Decorator
5. Facade
6. Flyweight
7. Proxy

Behavioral:
1. Iterator
2. Observer
3. Chain of Responsibility
4. Command
5. Memento
6. Mediator
7. State
8. Visitor
9. Strategy
10. Template

## Design Architectures
1. Model-View-Controller (MVC)






