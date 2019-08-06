# OPRECOMP

This is the Open [Transprecision Computing project], a joint venture between [IBM], [ETH], [CEA], [UNIPG], [UNIBO], [CINECA], [UJI], [QUB], [GWT], and [TUKL].

[Transprecision Computing project]: http://oprecomp.eu/ 
[IBM]: https://www.research.ibm.com/labs/zurich/
[ETH]: http://www.iis.ee.ethz.ch/
[CEA]: http://www.cea.fr/
[UNIPG]: https://www.unipg.it/
[UNIBO]: https://www.unibo.it/
[CINECA]: https://www.cineca.it/
[UJI]: https://www.uji.es/
[QUB]: https://www.qub.ac.uk/
[GWT]: http://www.greenwaves-technologies.com/
[TUKL]: https://www.uni-kl.de/

[OPRECOMP] is a 4-year research project funded under the EU Framework Horizon 2020 – Re Program Future and Emerging Technologies ([FET](http://cordis.europa.eu/programme/rcn/700395_en.html)) Proactive Initiative: [emerging themes and communities](http://cordis.europa.eu/fp7/ict/fet-proactive/minecc_en.html).

[OPRECOMP]:  http://oprecomp.eu/ 

## Contents

This is the main repository of the OPRECOMP project. Individual deliverables and development is performed in separate repositories, as follows:

- [oprecomp/micro-benchmarks](https://github.com/oprecomp/micro-benchmarks): A collection of benchmarks used throughout the project to assess the impact of transprecision techniques on a broad range of application fields.
- [oprecomp/FloatX](https://github.com/oprecomp/FloatX)
- [oprecomp/flexfloat](https://github.com/oprecomp/flexfloat) and [oprecomp/flexfloat-benchmarks](https://github.com/oprecomp/flexfloat-benchmarks)
- [oprecomp/HLS_BLSTM](https://github.com/oprecomp/HLS_BLSTM)
- [oprecomp/DRAMSpec](https://github.com/oprecomp/DRAMSpec)
- [oprecomp/RRAMSpec](https://github.com/oprecomp/RRAMSpec)


## Abstract

Guaranteed numerical precision of each elementary step in a complex computation has been the mainstay of traditional computing systems for many years. This era, fueled by Moore's law and the constant exponential improvement in computing efficiency, is at its twilight: from tiny nodes of the Internet-of-Things, to large HPC computing centers, sub-picoJoule/operation energy efficiency is essential for practical realizations. To overcome the “power wall”, a shift from traditional computing paradigms is now mandatory.

OPRECOMP aims at demolishing the ultra-conservative “precise” computing abstraction and replacing it with a more flexible and efficient one, namely transprecision computing. OPRECOMP will investigate the theoretical and practical understanding of the energy efficiency boost obtainable when accuracy requirements on data being processed, stored and communicated can be lifted for intermediate calculations. While approximate computing approaches have been used before, in OPRECOMP for the first time ever, a complete framework for transprecision computing, covering devices, circuits, software tools, and algorithms, along with the mathematical theory and physical foundations of the ideas will be developed that not only will provide error bounds with respect to full precision results, but also will enable major energy efficiency improvements even when there is no freedom to relax end-to-end application quality-of-results.

The mission of OPRECOMP is to demonstrate using physical demonstrators that this idea holds in a huge range of application scenarios in the domains of IoT, Big Data Analytics, Deep Learning, and HPC simulations: from the sub-milliWatt to the MegaWatt range, spanning nine orders of magnitude. In view of industrial exploitation, we will prove the quality and reliability and demonstrate that transprecision computing is the way to think about future systems.


## Contact

#### Project Management Office

    Cristiano Malossi
    IBM Research - Zurich
    Research Staff Member
    acm@zurich.ibm.com
    +41(0)44 724 8616

    Sara Pittaluga
    IBM Research – Zurich
    Business Development & Relations
    European Projects Specialist
    sar@zurich.ibm.com
    +41(0)44 724 8567

#### Repository and Software Management

    Fabian Schuiki
    ETH Zurich
    fschuiki@iis.ee.ethz.ch

    Florian Scheidegger
    IBM Research - Zurich
    eid@zurich.ibm.com


## License

The source code in this repository is licensed under the terms of the Apache License (Version 2.0), unless otherwise specified. See [LICENSE](LICENSE) for details.
