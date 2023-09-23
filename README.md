# Recovery of Phase Objects with Digital Holographic Microscopy.

## Holography, General Concepts.

The term hologram was coined by Denis Gabor in 1948 [Gue90]. The word comes from the Greek holos, which means complete [Hec00], and grafo, which means writing [Gue90]. In other words, hologram refers to the complete recording of something. Gabor used this term to describe the recording of the interference pattern between two beams in an electron microscope.

An interference pattern encodes the phase and amplitude information of the wavefronts analyzed into a single intensity pattern. This pattern can be recorded on conventional recording media. Most recording media, such as photographic plates, electrical sensors, and the human eye, can only record variations in light intensity. Therefore, the phase information of a wavefront cannot be directly recorded with these media.

In holography, only one of the beams contains the information we want to store and retrieve completely, both the amplitude and the phase. This beam is called the object beam, while the other beam is used solely to create the interference pattern and usually has a uniform distribution in both amplitude and phase and is called the reference beam or carrier wave. In contrast, in interferometry studies, the complexity of the two beams can be similar since the goal is to study the phase difference between the wavefronts and not the total recovery of one complex wavefront.

There is also a difference in the geometry of the interference experiments used in holography compared to those used in interferometry [Gue90]. However, the line separating these two branches of optics is very thin and allows for the application of methods developed for one branch in the other and vice versa. Since holograms are interference patterns, they follow the same restrictions imposed on the interference of two beams, which are as follows [Hec00]

- Only beams with the same polarization can interfere.
- Only beams with the same frequency interfere.
- The two beams must be mutually coherent, although partially coherent light is used in some cases.
- The ideal light source to ensure these three conditions is the laser. With the development of the laser in 1960, holography experienced a new boost [Gue90], making it possible to apply it in various areas, including digital holography.

## Hologram Recording

The action of generating an interference pattern and recording this pattern on a storage medium is known as hologram recording. In the case of digital holography, a device called a Charge-Coupled Device (CCD) is used as the recording medium. This way, the digitized information from the hologram is transferred directly to a computer. It is also possible to generate a hologram through computational means by mathematically simulating wavefronts. Once the matrix containing the interference pattern information is obtained, it can be printed to create a physical hologram or displayed on an electronic medium, such as a Liquid Crystal Display (LCD).

## Hologram Reconstruction

To recover the information encoded in a hologram (known as the object beam), a reconstruction process is required. Experimentally, this is achieved by illuminating the developed hologram with a wavefront that has similar characteristics to the reference beam used during recording. The only difference is that the illumination beam must propagate in the opposite direction to the hologram plane, which is called the conjugate of the reference beam, to form a real image of the object. Reconstruction can also be performed through computational simulations. In this case, the hologram is digitized and input into a computer as a data matrix to which mathematical models of light propagation are applied. This method is used in digital holography, which is the approach employed in this work.

## Types of Holograms

There are several classifications for holograms, based on the recording material, the angle between the object and reference beams, the object's position in relation to the hologram plane, and the type of reference wave. In this work, both in-line and off-axis amplitude holograms of the Fresnel type are used. Below are the characteristics of these types of holograms.

## Amplitude and Phase Holograms

An amplitude hologram consists of bright and dark fringes that primarily affect the amplitude of the reconstruction beam by obstructing part of it, according to the fringe pattern generated during recording. During the reconstruction stage, these holograms generate three different wavefronts the zeroth order, a real image, and a virtual image of the object. Phase holograms, on the other hand, introduce phase shifts at different points in the reconstruction beam, with minimal impact on its amplitude. The amount of phase shift at each point is related to the fringe pattern created during recording.