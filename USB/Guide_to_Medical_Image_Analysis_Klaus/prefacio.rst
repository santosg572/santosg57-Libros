Prefacio
========

Hans Castorp, in Thomas Mann’s Magic Mountain, keeps an x ray of his lover as it
seems to him the most intimate image of her to possess. Professionals will think differently of medical images, but the 
fascination with the ability to see the unseeable
is similar. And, of course, it is no longer just the x ray. Today, it is not sparseness, but
the wealth and diversity of the many different methods of generating images of the
human body that make the understanding of the depicted content difficult. At any
point in time in the last 20 years, at least one or two ways of acquiring a new kind
of image have been in the pipeline from research to development and application.
Currently, optical coherence tomography and magnetoencephalography (MEG) are
among those somewhere between development and first clinical application. At the
same time, established techniques such as computed tomography (CT) or magnetic
resonance imaging (MRI) reach new heights with respect to the depicted content,
image quality, or speed of acquisition, opening them to new fields in the medical
sciences.

Images are not self-explanatory, however. Their interpretation requires professional skill that has to grow with the number of 
different imaging techniques. The
many case reports and scientific articles about the use of images in diagnosis and
therapy bears witness to this. Since the appearance of digital images in the 1970s,
information technologies have had a part in this. The task of computer science has
been and still is the quantification of information in the images by supporting the
detection and delineation of structures from an image or from the fusion of information from different image sources. While 
certainly not having the elaborate skills
of a trained professional, automatic or semi-automatic analysis algorithms have the
advantage of repeatedly performing tasks of image analysis with constant quality,
hence relieving the human operator from the tedious and fatiguing parts of the interpretation task.

By the standards of computer science, computer-based image analysis is an old
research field, with the first applications in the 1960s. Images in general are such
a fascinating subject because the data elements contain so little information while
the whole image captures such a wide range of semantics. Just take a picture from
your last vacation and look for information in it. It is not just Uncle Harry, but
also the beauty of the background, the weather and time of day, the geographical
location, and many other kinds of information that can be gained from a collection of
pixels of which the only information is intensity, hue, and saturation. Consequently,
a variety of methods have been developed to integrate the necessary knowledge in
an interpretation algorithm for arriving at this kind of semantics.

Although medical images differ from photography in many aspects, similar techniques of image analysis can be applied to extract 
meaning from medical images.
Moreover, the profit from applying image analysis in a medical application is immediately visible as it saves times or increases 
the reliability of an interpretation
task needed to carry out a necessary medical procedure. It requires, however, that
the method is selected adequately, applied correctly, and validated sufficiently.

This book originates from lectures about the processing and analysis of medical images for students in Computer Science and 
Computational Visualistics who
want to specialize in Medical Imaging. The topics discussed in the lectures have
been rearranged to provide a single comprehensive view on the subject. The book
is structured according to potential applications in medical image analysis. It is a
different perspective if compared to image analysis, where usually a bottom-up sequence from pixel information to image content is 
preferred. Wherever it was possible to follow the traditional structure, this has been done. However, if the methodological 
perspective conflicted with the view from an application perspective, the
latter was chosen. The most notable difference is in the treatment of classification
and clustering techniques that appears twice since different methods are suitable for
segmentation in low-dimensional feature space compared to classification in highdimensional feature space.

The book is intended for medical professionals who want to get acquainted with
image analysis techniques, for professionals in medical imaging technology, and
for computer scientists and electrical engineers who want to specialize in the medical applications. A medical professional may 
want to skip the second chapter, as
he or she will be more intimately acquainted with medical images than the introduction in this chapter can provide. It may be 
necessary to acquire some additional
background knowledge in image or signal processing. However, only the most basic material was omitted (e.g., the definition of the 
Fourier transform, convolution,
etc.), information about which is freely available on the Internet. An engineer, on
the other hand, may want to get more insight into the clinical workflow, in which
analysis algorithms are integrated. The topic is presented briefly in this book, but a
much better understanding is gained from collaboration with medical professionals.
A beautiful algorithmic solution can be virtually useless if the constraints from the
application are not adhered to.

As it was developed from course material, the book is intended for use in lectures
on the processing and analysis of medical images. There are several possibilities
to use subsets of the book for single courses, which can be combined. Three of
the possibilities that I have tried myself are listed below (Cx refers to the chapter
number).

• Medical Image Generation and Processing (Bachelor course supplemented with
exercises to use Matlab or another toolbox for carrying out image processing
tasks):

– C2: Imaging techniques in detail (4 lectures),
– C3: DICOM (1 lecture),
– C4: Image enhancement (2 lectures),
– C5: Feature generation (1 lecture),
– C6: Basic segmentation techniques (2 lectures),
– C12: Classification (1 lecture),
– C13: Validation (1 lecture).

• Introduction to Medical Image Processing and Analysis (Bachelor course supplemented with a student’s project to solve a 
moderately challenging image analysis
task; requires background on imaging techniques):

– C2: Review of major digital imaging techniques: x ray, CT, MRI, ultrasound,nuclear imaging (1 lecture),
– C3: Information systems in hospitals (1 lecture),
– C4: Image enhancement (1 lecture),
– C6: Basic segmentation techniques (2 lectures),
– C7: Segmentation as a classification task (1 lecture),
– C8–C9: Introduction to graph cuts, active contours, and level sets (2 lectures),
– C10: Rigid and nonrigid registration (2 lectures),
– C11: Active Shape Model (1 lecture),
– C13: Validation (1 lecture).
• Advanced Image Analysis (Master course supplemented with a seminar on hot
topics in this field):
– C7: Segmentation by using Markov random fields (1 lecture),
– C8: Segmentation as operation on graphs (3 lectures),
– C9: Active contours, active surfaces, level sets (4 lectures),
– C11: Object detection with shape (4 lectures).
Most subjects are presented so that they can also be read on a cursory level,
omitting derivations and details. This is intentional to allow a reader to understand
the dependencies of a subject on other subjects without having to go into detail in
each one of them. It should also help to teach medical image analysis on the level
of a Bachelor’s course.
Medical image analysis is a rewarding field for investigating, developing, and
applying methods of image processing, computer vision, and pattern recognition.
I hope that this book gives the reader a sense of the breadth of this area and its many
challenges while providing him or her with the basic tools to take the challenge.
Magdeburg, Germany Klaus D. Toenni


