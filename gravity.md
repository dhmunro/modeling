Gravity and the Geometry of Motion
==================================

Introduction
------------

Two hundred and fifty years after Newton devised his wildly successful interlocking theories of motion and gravity, Einstein realized there was a radically different way to think about them.  Instead of Newton's inverse square force of attraction between masses, Einstein proposed that mass bends time to produce the acceleration of gravity.  While Newton treats gravity like other forces, Einstein treats gravity differently.  Other forces extend through space and time, while gravity warps the connection between time and space.

Specifically, Einstein focuses on the fact that gravity produces identical acceleration for every body, independent of its size or composition, as Galileo taught before Newton.  In Newton's view, it could have been otherwise - gravity could have accelerated wood at a different rate than stone or gold.  Newton performed careful experiments with pendulums to show that the downward acceleration of gravity is, in fact, identical among different materials to within a tenth of a percent - three decimal places.  This independence of gravitational acceleration from material composition has now been confirmed to better than fifteen decimal places using test masses inside a specially designed satellite orbiting the Earth.  Einstein embraces these experimental results by postulating that the acceleration of gravity is a built-in property of the geometry of space and time - its gradient turns out to be the intrinsic curvature of spacetime.  Thus in Einstein's model, the acceleration of gravity is inevitably independent of material composition.

How can Einstein's bizarre explanation of gravity as curvature be equivalent to Newton's common sense explanation of gravity as force?  Answering that question is our goal here.  Before we get started, you must be warned that this discussion does not follow the historical order or context in which Einstein developed his theories of Special Relativity and General Relativity.  In fact, the curvature interpretation of Newtonian gravity presented here was developed by Cartan, who back-engineered Einstein's General Relativity to the low speed limit (e.g.- the speed of anything in the solar system) where Newton's laws of motion and gravity are very nearly exact.  To understand the full theory of General Relativity, starting from Cartan's version of Newton's theory is easier than jumping directly from Newton to Einstein.  Here we focus on the change in perspective from Newton's picture of gravity to Einstein's, rather than the details of the treatment of absurdly high speed motion.  In this low speed limit, the two theories really are exactly the same - Einstein just shows you can interpret Newton's laws very differently from what Newton intended, and still be consistent with the centuries of evidence supporting Newton's interpretation.

We open with a brief review of Newton's laws of motion, followed by a longer review Kepler's laws of planetary motion and Newton's theory of universal gravitation.  We continue with a discussion of Newton's concept of space and time, in which space is like the frames of a movie and time labels the frames.  World-lines of bodies tie the frames together, but the First Law of motion singles out a particular class of possible frame stackings as "inertial reference systems".  Next, we contrast Newton's global with Einstein's local interpretation of the First Law.  In either case, the First Law serves as a straightedge for spacetime, determining which world-lines are straight, but Newton and Einstein disagree about which world-lines are straight in the case of gravity.  This tension leads Einstein to the concept of an intrinsically curved spacetime in which the connection between spatial slices (movie frames) of spacetime that varies from place to place.  We close with a discussion of the local reformulation of Newton's inverse square law due to Gauss, and how it naturally fits into Einstein's picture of a locally curved spacetime.


Newton's laws of motion
-----------------------

Newton's masterpiece, "The Mathematical Principles of Physics" - Principia for short - begins with a Definitions section, which includes a lengthy, almost apologetic, discussion of how he thinks about time and space.  In particular, Newton introduces or perhaps justifies his picture of absolute time and space, to which we shall return.  After these definitions, he presents his three laws of motion.  Paraphrased, they are:

First Law: A body at rest stays at rest, and a body in motion stays in motion in a straight line at constant speed, unless some net force acts upon it.

Second Law: The net force on a body is proportional to its mass and to its acceleration.

Third Law: To every action there is an equal and opposite reaction.  That is, if body A exerts a force on body B, then B exerts an equal and opposite force on A.

The Second Law is Newton's iconic formula F=ma, which serves as a definition of force or mass, or even, as we shall see, acceleration - at any rate a relation among three things.

The Third Law is now called "conservation of momentum," which is at first glance the only actual assertion being made about the physical world - you can't push on something without it pushing back on you.

An illustration from Galileo's masterwork "Dialogues Concerning Two New Sciences" shows a weight suspended by a rope from a cantilevered beam.  The picture suggests a way to think about force as tension in a rope, which transmits force from one end to the other.  The tension will always produce equal and opposite forces at the ends of the rope.  (Even when one side is winning a tug of war, the forces on the hands of the two teams are equal and opposite - it is the forces they are able to produce against the ground which differ.)  This is undoubtedly one of the pictures Newton had in mind when he formulated the Third Law: Imagine that any force between two bodies is transmitted by the tension of a thread (or compression of a rod) connecting them.  Much later, Faraday invented a similar picture of electric and magnetic field lines, which Maxwell showed act as innumerable tensioned threads connecting any two poles.  There is deep physics in the Third Law - it is a model for how bodies in the real world behave; it tells you the sense in which motion cannot be created or destroyed.

You may be puzzled by the First Law because it seems to be simply a special case of the Second Law, namely the case that the force and acceleration are both zero.  (Moving in a straight line at a constant speed, or not moving at all, is precisely what zero acceleration means.)  However, without the First Law, you don't really know how to measure acceleration - acceleration with respect to what?  You need some kind of a reference body you can take to be "at rest" - something relative to which you can measure position, hence velocity and acceleration.  "Relative to what?" is the question Newton is trying to answer with his lengthy discussion of absolute space preceding the laws of motion, and the purpose of the First Law is to answer that question.

The First Law tells you how to choose a reference body: Pick any body that has no net force acting on it - a free body.  If you have chosen your reference body according to the First Law, the Second Law tells your that any other free body will have zero acceleration relative to your reference.  That is, all free bodies move in straight lines at constant speed relative to one another, so no matter which free body you choose as your reference, all accelerations relative to it will be the same.  Thus, the physical content of the First Law for Newton is that acceleration is absolute - independent of whatever free body you choose as your reference for positions (and velocities).  But Einstein finds a loophole in the First Law, as we will see.


Newton's universal gravitation
------------------------------

Kepler's three laws of planetary motion distill millennia of astronomical observations, improving upon the already quite accurate ancient Greek system of epicycles described in Ptolemy's Almagest.  But unlike the Greeks, Kepler does not guess the distances to the planets; he surveys them, using pure geometry and a brilliant trick involving the periodicity of planetary orbits.  Working from naked eye observations alone before the invention of the telescope, Kepler discovered: (1) Planetary orbits are ellipses with the Sun at one focus and a fixed orientation with respect to the distant stars, (2) A radius drawn from the Sun to the planet sweeps over equal areas in equal times (so they move faster when closer to the Sun and slower when farther away), and (3) Comparing the orbits of the several planets, the cube of the major axis of their ellipse is proportional to the square of their orbital period.

Newton wrote Principia about three quarters of a century after Kepler.  Galileo had invented the telescope at essentially the same time Kepler was publishing his laws, and by Newton's time, astronomers knew that four moons of Jupiter and five moons of Saturn also obey Kepler's laws with respect to their planet; Kepler's laws of planetary motion had become Kepler's laws of orbital motion more generally.  (The constant of proportionality in the cube-square law is different for the Sun, Jupiter, and Saturn, however.)  After formulating the Second Law, F=ma, Newton would naturally ask what sort of force must be acting on the planets in order to keep them in their orbits?

To keep an object in circular motion (though ellipses, planetary orbits are very nearly circular) obviously requires a central force - a force directed toward the fixed point at the center of the orbit.  Just think about tying a stone to a string and whirling it in a circle - the string is obviously pulling the stone directly toward the center.  Hence it is not surprising that after stating his laws of motion, Newton immediately turns his attention to how a body moves when the force on it is always directed toward toward some fixed central point - a centripetal force.  You can get non-circular orbits if you vary the tension in the notional string connecting the center point to the body (by pulling in or letting out more string), so the magnitude of the central force may vary, but the direction of the force is assumed to be toward a fixed center.

Newton's very first result is that for any centripetal force, the radius drawn from the center point to the body sweeps out equal areas in equal times, and the motion remains in a single plane containing the center point.  Thus, Kepler's second law of planetary motion is an immediate consequence of F=ma, assuming the force holding the planet in its orbit is always directed toward a fixed point.  Newton also proves the converse: If you observe any body to move such that its radius to some fixed point sweeps out equal areas in equal times, then that body must be experiencing a force always directed toward that point.  Right out of the gate, Newton has shown that the planets experience a force always directed toward the Sun!  Furthermore, the moons of Jupiter always accelerate directly toward Jupiter, and the moons of Saturn directly toward Saturn!  Today, Kepler's equal area law is called "conservation of angular momentum"; again, it is a consequence of F=ma for any centripetal force.

Because of Kepler's equal area law, all possible motion under any centripetal force must happen in a single plane containing the center of force.  Furthermore, since the area swept out is proportional to time, area in the plane of motion can be taken as a surrogate for time, and the entire problem reduces to a study of curves in plane geometry.  Newton is very, very good at geometry, and he proceeds to work out exactly how the force (or rather acceleration, since the mass of the body is fixed) must vary from place to place in order for the trajectory of the body to follow half a dozen simple plane figures.

Needless to say, one of the figures he chooses is an ellipse from Kepler's first law of planetary motion.  That is, Newton asks, "How must the centripetal force on a body vary in order for its trajectory to be an ellipse with the center of force at one focus?"  Working through the geometry, he finds that the force must vary inversely as the square of the distance from the center.  He finds the same inverse square law is required for the body to follow a hyperbolic or parabolic trajectory with the center at one focus - any conic section.  (The hyperbola is interesting because one of its two branches is the case of a repulsive inverse square force; the other orbits all require attractive inverse square forces.)

Some other figures Newton works out are an elliptical trajectory with force directed to the center of the ellipse instead of to a focus, an Archimedean spiral trajectory with center at its endpoint, and a circular trajectory with the center on the perimeter of the circle.  These require, respectively, force directly proportional to distance, force inversely proportional to the cube of distance, and force inversely proportional to the fifth power of distance.  He's having so much fun you can feel his joy through all the Euclidean formality.

Now that Newton has shown an inverse square law of centripetal force is mathematically equivalent to Kepler's first two laws of planetary motion, all that remains is Kepler's cube-square law relating the orbits of multiple satellites around a common center.  For the case of circular orbits, the cube-square law is obvious, inasmuch as acceleration scales as distance divided by the square of orbital period, and itself scales inversely with distance squared.  In fact, the constant of proportionality in the cube-square law is the same as the constant of proportionality in the inverse square acceleration law, to within some factors of two pi.  To wrap up the case, Newton compares circular and elliptical orbits sharing a common inverse square acceleration law.  He shows that their orbital periods match when the major axis of the ellipse equals the diameter of the circle (which is also its major axis).

Hence, for any orbital shape, Kepler's third law means that all the planets (or moons) accelerate toward the Sun (or planet) according to a single inverse square acceleration law.  If you know how far anything is from the Sun, you know how fast it is accelerating toward the Sun.  Similarly, you know how fast any body accelerates toward Jupiter from its distance to Jupiter or toward Saturn from its distance from Saturn.

To put a cherry on top, Newton points out that if you take the acceleration of gravity we measure at the surface of the Earth, and diminish it by 3600 - the inverse square of the 60, the distance between the Moon and Earth measured in Earth radii - you get the measured acceleration of the Moon toward Earth.  The force of gravity we feel on Earth extends to the Moon and holds the Moon in its orbit!  Newton has not simply shown that an inverse square acceleration law is mathematically equivalent to Kepler's three laws of planetary motion, he has demonstrated that this inverse square force is none other than the force of gravity we have always known.  Not only are the planets moving according to F=ma like any stone we throw, but also the force holding planets in orbit is the familiar pull of gravity.  This is pretty easily the greatest Eureka moment in the history of human thought - Newton has literally connected heaven to Earth.

But there's more, much more.  From the moons of Jupiter and Saturn as well as our Moon and Earth, in addition to the planets and Sun, Newton has demonstrated that the Sun, Jupiter, Saturn, and the Earth each causes a gravitational acceleration toward any body in its neighborhood, which decreases inversely as the square of distance from it.  It's a small step to imagine this inverse square law of gravity is an innate property of all bodies, even if it is an imperceptibly small force between any pair of bodies much smaller than planets.  Hence, Newton postulates that his inverse square law is a universal force of gravitation acting between any pair of bodies whatsoever.

Furthermore, Newton has only used his Second Law of motion to prove all of this!  What does the Third Law tell him about his inverse square law of gravity?

Since gravity accelerates all bodies at the same rate - an experimental fact - the Second Law means force of gravity must be proportional to the mass of the body being pulled, be it a small weight on Earth's surface, a moon, or a planet.  By the Third Law, that smaller body must be exerting exactly the same force as the gravity of the larger body exerts upon it - you must be pulling upward on the Earth with exactly the same force the Earth pulls downward on you according to the Third Law of motion.  That counterforce can be none other than the gravitational attraction of your body, since it must vary inversely as the square of the distance from you!  Hence the force of gravity must be proportional not only to the mass of the body being pulled, but also to the mass of the body doing the pulling - that's the only way the force and counterforce can be equal and satisfy the Third Law.  Not only does gravitational force a body experiences proportional to its mass, but the gravitational force it exerts on other bodies must be proportional to its mass by the Third Law.  (The reasoning which led Einstein to the field equations of General Relativity is based on this intimate connection between gravity and conservation of momentum.)

Thus, the gravitational force between two bodies is proportional to the product of the two masses and inversely proportional to the square of their distance.  The constant of proportionality - Newton's gravitational constant - is the first universal constant ever discovered.  Newton computed its value when mass is measured in units of solar masses or Earth masses, but the experiment required to measure its value with mass in units of kilograms - measuring the gravitational attraction between two bodies with known masses in kilograms - is extraordinarily difficult, and wasn't successfully carried out until a century after Principia.


World-lines and the direction of time
-------------------------------------

We very naturally think about motion as rapid succession of snapshots or frames, each capturing some group of objects at a single instant of time, because that is exactly how we make movies or videos or any animation.  When the snapshots are presented in rapid sequence, we interpret changes in position of the objects from frame to frame as motion.  Although the frames of a movie or video are two dimensional, it is easy to imagine a succession of three dimensional frames, each depicting some group of objects at a different instant of time.  Euclidean geometry governs each individual frame - that's exactly what Euclid was trying to capture - so we know all about straight lines, circles, distances, angles, and so on in each frozen snapshot.  The problem comes when we try to connect the successive frames of our movie, and that connection is what Newton is addressing with his discussion of absolute time and space.

For two dimensions of space, you can imagine each snapshot is reproduced on a card, where each card represents one instant of time.  For example, imagine positions the Sun and inner planets (as viewed from far above the ecliptic plane) at successive times are marked on each card, so you can label each card by the time of its snapshot.  When we talk about spacetime, we are talking about the whole deck, stacked in order, and we are interested in the geometry of that whole stack.  But when you place each card atop the previous one, how do you know where to put it?  These cards have no edges to line up.  In fact, in the case of the solar system cards, Ptolemy used the Earth to align successive cards the deck, while Copernicus used the Sun - geocentric stacking versus heliocentric stacking.  In general, you are free to slide the cards around however you wish: What does it mean to be "at the same place" at two different times?  Relative to the Earth? to the Sun? or to something else entirely?

However you stack the spatial slices, when you connect the position of any material body on one slice to its position on successive slices, you get a (possibly curved) line which runs out of the spatial dimensions through the time dimension.  This is called the world-line of the body.  Spacetime geometry is more about these world-lines than about the points (called events) along them.  When you use any particular body as your reference guide for stacking spatial slices, its world-line becomes a straight line which cuts through spacetime perpendicular to the deck in our card model, as does the world-line of any other body which is at rest relative to the first.  Bodies moving with constant velocity (speed and direction) relative to the reference body will also have straight world-lines, but tilted away from the perpendicular to the card deck.  The world-lines for other bodies will be distorted into various curves - in the solar system example every body except whatever you choose as a reference will corkscrew through the card deck.

As you sit in your chair, you can easily point forward, backward, left, right, up, or down - corresponding to the three pairs of opposite directions in three dimensional space.  If you want to think about spacetime geometrically, then future and past must correspond to a fourth direction - your time direction.  Going back to the card deck analogy, the direction of time must punch through the deck, just like every world-line.  If you stack the card deck so that you and your chair are at rest, then your direction of time must be along your world-line, perpendicular to the cards in the deck.  But perhaps you look out your window and see someone driving by in a car.  Their world-line will be tilted as it cuts through your card deck - thus, their direction of time is not the same as yours!  The direction of time varies from one observer to another, depending on how fast and in what direction they are moving.

This is no different from the fact that the spatial directions like left or right depend on what direction you are facing.  The direction of time, like the direction rightward, is relative.  Velocity measures the tilt of world-lines, hence the tilt of the time direction relative to some particular card stacking, similar to the way that angle (or more accurately, slope) measures the tilt of rightward for you relative to rightward for someone standing nearby.  If their rightward is different from yours, it means they are facing in a different direction.  If their time direction is different from yours, it means they are moving with a different velocity.

To summarize, the direction of time runs along world-lines, and motion tilts the direction of time in the same way that rotation tilts spatial directions.  But in addition to relative directions like rightward, we also have absolute directions like north (taking "north" in its astronomical sense to mean Polaris-ward).  Is there an absolute direction for time?  Newton says yes - that's what his discussion of absolute space and time is about.  However, he concedes that, like north, there is an arbitrariness about exactly what choice you make for the standard direction of time.  There is no preferred state state of motion, any more than there is a preferred direction in space.

Newton suggests using the world-line of the center of mass of the entire solar system, which is called the solar system barycenter (SSB), as a practical realization of an absolute direction of time.  He proves that, according to the laws of motion, this point moves at a constant velocity relative to any distant body which has no forces acting upon it.  Note that the center of the Sun moves around the SSB as the configuration of the planets change due to their various orbits.  Thus Newton's solar system model is not heliocentric, a fact generally overlooked.  Newton has rendered the revolutionary ideas of Copernicus moot (if not silly) less than a century and a half after that controversy ignited.  The world-line of the solar system barycenter, always within about a solar diameter of the center of the Sun, is the practical absolute direction of time to this day, used by all modern astronomers.

Incidentally, the practical absolute direction in space, called the International Celestial Reference Frame or ICRF, is based on the directions to several hundred extremely distant quasars evenly scattered throughout the sky.  This is not how Newton could have dreamed of defining spatial directions, so his use of the SSB as a reference time direction has, at least in some respects, outlasted his reference spatial directions.

Notice that although the tilt of a world-line - the velocity of the body - is completely unrestricted, it cannot tilt backward in time.  The direction of time differs from any spatial direction in that particular, since you can reorient yourself in space to make any direction at all be rightward.  The reason is simple: you would never interpret a world-line to point backward in time - if the body were following such a world line, you would interpret it as moving forward in time with the opposite velocity.  But even including both directions along it, no world-line can point directly along any spatial direction.  Again, the reason is simple: no body can be in two (or multiple) places at once.  Hence, there are technically two different kinds of directions in spacetime, called timelike directions - directions a world-line can lie along - and spacelike directions - the directions in ordinary space at any given instant of time.

Einstein was the first to realize that this structure is not quite correct when bodies move ridiculously fast, which he did a decade before his theory of gravity.  It turns out that the distinction between timelike and spacelike directions in spacetime is still important, but that the spacelike directions are not quite restricted to directions in ordinary space, since no world line can tilt faster than light.  But we will continue to ignore that high speed detail of the story here - it is a plot complication that distracts from the more important new perspective Einstein brings the story of gravity.


Using the First Law as a straightedge
-------------------------------------

So far, spacetime isn't much of a geometry.  A collection of world-lines seems more like a tangle of spaghetti; the shape of each strand depends entirely on how you choose to stack the spatial slices of spacetime - how you align successive cards in the deck.  In geometry, Euclid's first two postulates define straight lines; the practical embodiment of those two postulates is the straightedge.  Newton writes very beautifully about the relation between abstract geometry and practical mechanics in the preface to Principia:

    To describe right lines and circles are problems, but not geometrical problems. The solution of these problems is required from mechanics; and by geometry the use of them, when so solved, is shown; and it is the glory of geometry that from those few principles, brought from without, it is able to produce so many things. Therefore geometry is founded in mechanical practice, and is nothing but that part of universal mechanics which accurately proposes and demonstrates the art of measuring.

By his laws of motion, Newton clearly intends to extend these mechanical underpinnings of Euclidean geometry from position in space to motion in spacetime.  If we had a straightedge for spacetime, we'd have the beginnings of a real geometry of spacetime.  But the First Law is exactly the straightedge we need for world-lines!  If you can find any body which has no net forces acting upon it, the First Law says it is either at rest or moving with constant speed and direction - in either case, its world-line must be a straight line through spacetime.  This drastically narrows down the ways you are permitted to stack the spatial snapshots to build up spacetime, since every body experiencing no net force can at most be moving at a constant speed in a fixed direction relative to your reference body.  This is just like Euclid's straightedges - you can tilt your spacetime straightedge to make it point in whatever time direction you choose.

Now Newton presumes that an body very far from any other will have no significant external force acting upon it; by the First Law, such a remote body must have a straight world-line.  This single remote body may therefore serve as a reference, determining how to stack the spatial slices throughout all of spacetime.  He demonstrates that the center of mass of the entire solar system (the SSB) must move in a straight line through spacetime with this same stacking; thus, to the extent that the solar system is far from anything else, he doesn't need to rely on a hypothetical remote body to stack the spatial slices.  With this global stacking, the world-lines of the planets and satellites are all curved, corkscrew-like paths through spacetime.  Some force must causes those world-lines to curve, and we have seen how Newton uses the Second and Third Laws to work out universal gravitation.

Despite the wild successes of Newtonian gravity, Einstein is uneasy with Newton's interpretation of the First Law: When you are falling, you feel no forces acting upon you - orbiting astronauts are weightless!  Why shouldn't the First Law require that you be moving in a straight line at a constant speed?  Any material body will develop internal stresses when a net external force is applied to its surface, like the rope in Galileo's illustration of a suspended weight.  Newton's answer to this criticism is that gravity acts directly on each small part of the material in a body, so unlike a rope that pulls only on its attachment point, gravity produces no differential forces inside a falling body and hence no internal stresses.

In a way, Newton's answer works a little too well - it applies not only to the individual parts of a single body which are at rest relative to one another, but also to any nearby bodies that may be falling at different instantaneous speeds - these also experience the same gravitational acceleration as the first body, so relative to that body, they continue moving in straight lines with fixed directions.  That is, any collection of freely falling bodies nearby that first body obey the First Law locally among themselves.  Einstein points out that locally this collection of freely falling nearby small objects would look exactly the same if the whole collection were removed to a remote location, but observed from an accelerated vantage point.  In other words, at least locally, the action of gravity is indistinguishable from adopting the viewpoint of an accelerated observer.  (Interestingly, Newton actually calls attention to this feature of the relative motion of a collection of objects in Principia as well.)

Therefore, Einstein proposes that instead of Newton's global stacking of spatial slices to build a complete model, we should allow ourselves to use many local stackings, and figure out how to piece them together into a complete whole.  Newton imagines a global connection between snapshots, while Einstein imagines many local connections, so different parts of each snapshot connect to corresponding parts of adjacent snapshots differently.  From a global perspective, this is obviously dramatically more complicated than Newton's picture.  The only thing Einstein's picture has going for it is that a local interpretation of the First Law is more practical - if a body has no internal stresses, you can use it as a reference body locally.  The difference between Newton's and Einstein's pictures of gravity is that Newton takes a global view of the meaning of acceleration (the stacking of spatial slices), while Einstein takes a local view.


Does the ground accelerate upward?
----------------------------------

Let's look at a concrete example: Watch two balls drop from different heights and bounce.  In physics lectures they often use a ball bearing dropped onto a heavy steel plate, which can bounce for several minutes, returning to nearly the same height on successive bounces.  Except for the instant(s) of contact, both balls are in free fall.  The motion is in one spatial dimension - vertical - so we can easily draw the world-lines of these balls in spacetime by plotting time horizontally.  Each of our one dimensional spatial snapshots records three vertical positions - the ground (where they bounce) and the two balls.

Newton says that the force of gravity constantly accelerates each ball downward, so its trajectory on each bounce curves in a parabola through spacetime.  The ground, on the other hand, remains at a fixed height, held there by the gradually increasing pressure reaching all the way through the Earth.  In order to judge that the balls are accelerating downward, Newton is implicitly using the ground (or the center of the Earth) as his reference body to stack the snapshots, so that he plots the ground as a straight horizontal world-line in our diagram.

Einstein says that since the balls are in free fall between bounces, unstressed by any external forces, we should stack the snapshots so that every bounce of both is a straight world-line rather than a parabola.  The velocity or tilt of these world lines of course change at the moment of each impact, when the ball certainly does experience very large internal stresses and thus changes velocity very rapidly.  In any stacking with this property, the ground will follow an upward curving parabola, that is, the ground is accelerating upward at one gee in Einstein's picture of spacetime.

Notice that with a single stacking, Einstein turns every bounce of both balls into a straight segment of their world-lines, despite the fact that their relative velocities differ and change with each bounce.  This is because the acceleration of every ball in Newton's stacking was one gee downward, no matter what its instantaneous velocity.  Notice that Einstein has a very simple explanation for Galileo's observation that all objects accelerate downward at the same rate relative to the ground: It's the ground that accelerates upward at one gee - the acceleration doesn't belong to the freely falling objects at all - their world-lines are all straight!  By keeping the ground "at the same place" for all times, you have chosen an accelerated reference frame, so naturally anything you observe from that viewpoint will appear to share the opposite acceleration.

But what happened to gravity in Einstein's picture?  If there is no such thing as a force of gravity, what keeps the planets orbiting the Sun?  The problem is that Einstein's stacking of spatial slices only works as long as Newton's acceleration of gravity does not change from place to place.  The Earth is a globe, after all, and on the opposite side from where you sit, their down is your up - the acceleration of gravity is in completely the opposite direction.  Hence Einstein's stacking can only apply locally - he has to use a different stacking on the opposite side of the Earth.  Although the downward acceleration of gravity remains pretty nearly the same within a few kilometers of where you are sitting, it begins to change at distances which are a significant fraction of the size of the Earth.  So you can use Einstein's stacking within a few kilometers (and a few minutes) of where you are, you cannot use it globally.

Imagine that the Earth weren't spinning, and that you drill a hole straight through its center and out the opposite side.  Newton's acceleration of gravity toward the center must decrease gradually as you move down the hole to zero at the center, then increase back to one gee in the opposite direction when you reach the other end of the hole.  Splitting the hole into a number of segments each a few kilometers long, Newton's acceleration of gravity changes very little within each segment, so you can apply Einstein's stacking to each segment individually.  This produces a whole family of parabolas, each a few kilometers in vertical extent, but each covering as wide an extent of time as you please.  The curvature of the parabolas gradually decreases until you reach the central one, which is a straight horizontal line - Einstein's stacking and Newton's stacking agree at the center of the Earth.  Continuing down the hole, Einstein's parabolas gradually become more and more curved downwards.  This is what Einstein means by a local stacking of snapshots - each local stacking is almost but not quite consistent with adjacent stackings, causing the gaps (or in other cases overlaps) between adjacent parabolas in this example.


Intrinsic curvature of spacetime
--------------------------------


Local formulation of inverse square law
---------------------------------------






In a plot of position versus time, every body follows a line called its world-line.  Even a body at rest extends in the direction of time.  In a sense, spacetime is a geometry of lines - world-lines - rather than points.  You may need to think of points in spacetime - called events - as the intersection of two world lines, rather than thinking of a line being determined by two points as Euclid would have it.  You can make any world-line straight by simply choosing that body to be the reference for position, the origin of your position coordinates.  Another way to say this is that you can adopt any world-line to define the direction of time in your coordinate system, since after the time direction is nothing more than the spacetime direction in which your position coordinates have fixed values.

Another way to think about the First Law is that it identifies straight lines through spacetime.  When you plot position versus time, a body moving with constant (possibly zero) velocity appears as a straight line; conversely, an accelerated body follows a curved path in your space-time plot.  As long as gravity is negligible, Einstein agrees with Newton on this interpretation of the First Law, but when gravity is important they will part ways.

Absolute space and time versus curved spacetime
-----------------------------------------------

Gauss's local reformulation of the inverse square law
-----------------------------------------------------

Einstein's fusion of Gauss's law and curved spacetime
-----------------------------------------------------







Newton's universal gravitation
------------------------------

While Newton's laws of motion are a theoretical framework meant to be applied generally to all possible causes of motion, his theory of gravity addresses only one specific force.  His goal is to explain just the phenomena associated with gravity.  In the process he manages to realize that many things which were previously unknown to have any relation to gravity are, in fact, explained by his theory - for example, celestial motions and the tides.  The realization that the force of gravity holding you in your chair also holds the planets in their orbits is arguably the greatest scientific breakthrough in history, radically reshaping the role of science in human thought, as well as guiding and inspiring the technological revolution that continues to this day.

Newton divides Principia into three books.  Book I begins with the Definitions and Laws of Motion, as we have seen, then continues with a ten pages that amount to the invention of calculus and an explanation of how this new mathematical tool can be used to compute the mathematical consequences of the Second Law of motion, F=ma.  Most of the remainder of Book I is devoted to a hundred pages working through how a body moves when it feels only a centripetal force, that is, a force always directed toward a fixed center point but may changing in magnitude from one place to another.  His first example is what we today call conservation of angular momentum, showing that the radius drawn from the fixed center point to the body sweeps out equal areas in equal times, and always remains in a single plane.  Armed with the fact that the motion of a body under any centripetal force is confined to a plane, Newton works through exactly how a centripetal force has to vary for its trajectory to follow a wide variety of different simple plane curves: For example, an inverse fifth power force law produces a circular trajectory with the center of attraction on the perimeter of the circle, and an inverse cubic law produces an Archimedean spiral trajectory with its endpoint at the center.  Ans so on.

In the midst of these exercises, we find the cases of the conic sections - ellipses, hyperbolas, and parabolas, with the centripetal force directed toward a focus of the figure.  To trace any of these figures, the central force must vary inversely as the square of the distance.  Newton concentrates on this case, showing that if several bodies are following elliptical trajectories under the influence of a single inverse square centripetal force directed toward their common foci, then the cube of the major axes of their ellipses will be proportional to the square of their orbital periods.  The case of ellipses with the center of force at one focus, the general equal areas in equal times rule, and the cube-square law relating orbital size and period are exactly Kepler's three laws of planetary motion, all three follow from an inverse square force law.  But Newton doesn't mention that yet - he's just working through a bunch of mathematical examples of how to apply calculus to work out trajectories for different centripetal force laws.

Book II concentrates on bodies moving through fluids, birthing the modern fields of hydrodynamics and aerodynamics, or fluid mechanics in general.  Unlike Book I, this is not entirely mathematical - Newton is at least selecting the motions he works out based on his considerable physical insight into how fluids move.

Book III returns to the physical implications of the math he worked out in Book I.  It begins with a philosophical discussion of rules of inference and the role of math in natural science.  Newton continues by introducing his theory of universal gravitation, that all bodies are attracted to each other in proportion to both masses and inversely proportional to the distance between them.  He proceeds to demonstrate how this single law explains an astonishing variety of phenomena, which hitherto were unknown to be related.  These include not only the gravity we daily experience, but the motions of the planets and moons in the solar system, how our Moon causes tides, an astonishingly detailed explanation of the many small inequalities in the orbit of the Moon which had puzzled astronomers for millennia, the precession of the equinoxes discovered by Hipparchus two thousand years earlier, and the plunging orbits of comets.  The phrase "tour de force" does not begin to describe the impact of these hundred pages.

















Here we will see how Einstein's bizarre explanation of gravity as curvature is equivalent to Newton's common sense explanation of gravity as a force, despite compelling you to describe the motion of projectiles using completely different words.  The lesson is that there's more than one way to think about the world around us, not that Newton was entirely wrong nor Einstein entirely right.  Newton's ideas about force and motion are and will remain incomparably more important than Einstein's for thinking about the phenomena of everyday life.  Einstein himself was a fervent disciple of Newton, perhaps the last great champion of Newtonian determinism, and even in Einstein's model of gravity, Newton's laws of motion apply for every kind of force except gravity.

So why did Einstein produce such a different description of gravity?

Einstein's ideas evolved from trying to work out some deeply puzzling features of Maxwell's theory of electromagnetism (undoubtedly the second greatest achievement in physics after Newton).  Einstein was the first to realize that Newton's ideas of absolute space and time were inconsistent with Maxwell's equations: When you consider extremely rapidly moving bodies - thousands of times faster than the fastest bodies in the solar system - space and time become inextricably connected in completely counterintuitive ways.  Remarkably, Newton's laws of motion still apply, but without his notions of absolute time and space, words like "mass" and "force" used in those laws must be interpreted somewhat differently when you try to apply them to very rapidly moving objects.  Changing what you mean by "time" and "space" pulls the rug out from under any laws which implicitly depend upon them.  Nevertheless, Einstein succeeded brilliantly at modifying Newton's ideas of space, time, mass, and force to bring them into perfect consistency with the unmodified Maxwell's equations.  The iconic formula E=mc^2 is the epitome of this work, which he called Special Relativity, but none of this has anything to do with gravity.

The problem Einstein faced was that, just as Maxwell's electromagnetism was incompatible with Newton's formulation of the laws of motion, Newton's gravity was incompatible with Einstein's formulation of the laws of motion!  Although Newtonian gravity is simpler than electromagnetism, Einstein couldn't find any easy tweak to bring it into compliance with his new ideas about space and time.





Instead of Newton's force of attraction between bodies, Einstein's gravity is a distortion or curvature in the combined geometry of time and space produced by any material body.  The cumulative effect of this curvature in the space between two bodies causes them to accelerate toward each other in the absence of any force between them.

What does acceleration have to do with curvature?  The word "curvature" conjures an image of a curved surface in space, maybe a car fender - or a rubber sheet in a popular depiction of Einstein's concept of gravity.  But the curvature Einstein is talking about is (almost entirely) a curvature in the direction of time, not any bending or distortion of space.  This sounds rather mystical at first, but Einstein doesn't mean anything more than this: When you plot position versus time, the path of an accelerating body is curved.  (Because a body moving at constant speed follows a straight line in a position-time plot.)  Strictly speaking, as we will see, Einstein's spacetime curvature is the gradient of the acceleration from place to place, but when you hear the words "spacetime curvature" you should think about curved paths in a position-time plot, not car fenders or rubber sheets.  Spacetime curvature distorts the connection between space and time, not any snapshot of space at a single time; it changes how bodies move, not where they are.

What does it mean to be at the same place but different times?  What does it mean to be at the same time but different places?  Einstein's theory of general relativity addresses the first question; his theory of special relativity addresses the second.

Affine geometry is the geometry of straight lines, plus parallel transport of lines.

Action at a distance becomes boundary conditions in field theories?

---------------------------------------------------------
Newton's Laws of Motion and Gravity

Modern physics began when Newton laid down his three laws of motion and an
additional universal inverse square law of gravitational attraction among all
bodies.  The realization that the downward pull of gravity we all feel extends
out to the Moon, Sun, and planets, and governs their motion as surely as the
motion of a thrown ball is arguably the greatest "Eureka" moment in history.

To begin to appreciate the amount of human effort and ingenuity behind Newton's
theory, you need to understand the technical difficultly of the problems
people had to solve to get him to that point.  Those details are usually skipped
over in popular accounts, which always left me wondering how anyone managed to
figure them out.  My goal is to fill in those technical arguments so you can
follow with a minimum of math.  Hopefully the three centuries of hindsight
since Newton makes that possible; after all many great physicists have studied,
rethought, and rechecked these very problems many times over all those years.

Newton's Laws of Motion and Gravity
1. Prelude: What ancient Greek astronomers did
  - size of Earth, distance to Moon, ecliptic, motion of the Sun (Eratosthenes)
  - precession of equinoxes, star charts, epicycle model (Hipparchus)
  - Almagest accurate sidereal periods of planets (Ptolemy)
2. What Kepler did
  - exploit sidereal periodicity to determine points on orbits of Earth, Mars
  - fit Mars to ellipse, epicycle deviation only detectable by Tycho accuracy
  - equal areas in equal times (replacing complicated deferent schemes)
  - first two laws model of Earth plus few observations fix unknown orbits
  - cube-square law
3. What Galileo did
  - use telescope to discover moons of Jupiter, phases of Venus
  - Kepler notices that moons of Jupiter obey cube-square law (at least)
  - relativity and rudimentary principle of equivalence
  - gravitational acceleration same for all objects
4. What Newton did
  - inertial reference frames, F=ma
  - central force equivalent to equal area law (angular momentum)
  - ...implies angular velocity is inverse square
  - elliptical orbits plus equal area implies eccentric circle in velocity
  - ...implies acceleration is inverse square
  - cube-square law implies same inverse square constant for all planets
  - acceleration of Moon is 60**2 time less than surface gravity, thus
    force holding planets in orbit is gravity, all objects attract one another
  - action=reaction implies inverse square constant proportional to mass
  - three body explanation for irregularities of orbit of Moon
  - tides as combination of gravity, centrifugal force gradients
  - ?initiates study of fluid mechanics
5. Postscript: What Gauss did
  - field plus divergence theorem as local theory of gravity
  - intrinsic curvature of surfaces

------------------------
Einstein's Laws of Motion and Gravity

In the first two decades of the twentieth century, Einstein shocked the world
with his special and general theories of relativity, replacing Newtonian
mechanics and universal gravitation by a new formalism consistent with Maxwell's
equations of electromagnetism.  Newtonian mechanics was - and still is - the
foundation of every field of physical science and engineering, so it just isn't
possible that Einstein completely overthrew Newton.  In fact, he very deftly
ensures that his new models of mechanics and gravity almost exactly match
Newton's as long as nothing is moving at speeds comparable to the speed of
light.  What Einstein did, therefore, was to extend Newton's theories of motion
and gravity into the largely unexplored territory of extremely high speed
motion.

The big surprise is that our intuitive notions about the nature of time, as
embodied by Newtonian mechanics, no longer correspond to the reality of very
rapid motion.  

My goal here is to explain what Einstein did with a minimum of algebra, but
without skipping any of the physical concepts you need to understand how
modern physicists think about space and time, at least on macroscopic scales.
The mathematics of special relativity - the theory of how things move in the
absence of gravity - is easy, at the same level as the coordinate geometry
taught in every high school.  On the other hand, the mathematics of general
relativity - the theory of how things move in the presence of gravity - is
extraordinarily difficult, far beyond what even the typical PhD student in
physics or mathematics ever masters.  But this distinction between the math of
the special and general theories won't really matter here.  For understanding
their physics, both the special and general theories present significant
challenges, but in very different ways.

No human experience could possibly lead you to think about motion - that is,
about time and space - as special relativity describes it.  You must rely
entirely on the results of esoteric experiments involving either bodies moving
at inhumanly high speed, or on inhumanly high precision clocks and rulers.
Worse, the experimental facts contradict the common usage of the only words in
our human languages to describe them.  For example, "They traveled twice as
fast," and "They arrived in half the time," mean the same thing in ordinary
language, but not in special relativity.  So the conceptual problem you face
with special relativity is that experimental fact conflicts with your intuition
when things move at very high speed.

Rather than reconciling a conflict between your intuition and reality, the
conceptual problem with general relativity is teaching yourself a very
different way to interpret commonplace observations.  Einstein asks you to
imagine that the surface of the Earth is accelerating upwards and pressing
against your feet, rather than that gravity is pulling you downwards.  Instead
of forcing you to accept that reality is different than you imagined, general
relativity requires you to acknowledge that there is a very different way to
interpret and describe the familiar effects of gravity.  Instead of a force of
attraction between material bodies, gravity can be described as a curvature of
spacetime caused by material bodies.  This new perspective is rarely the
simplest way to picture phenomena involving gravity, but is indispensable when
things are moving very fast or when you need extremely precise answers.

The connection between the laws of gravity and motion is very deep for both
Newton and Einstein.  For Newton, the fact that for every action there is an
equal and opposite reaction - his third law of motion - enables him to infer
that your body pulls the Earth upward with exactly the same force that the
Earth pulls your body downward.  A law of motion, which today we call
conservation of momentum, thus leads Newton to conclude that gravity is a
universal force of attraction between every pair of bodies, proportional to the
mass of each.  Einstein, on the other hand, constructs his theory of gravity
so that conservation of mass and momentum - which governs motion of bodies -
becomes a geometrical identity, in a manner analogous to the way Maxwell added
the final term to his theory of electromagnetism in order to make conservation
of charge an algebraic identity.




Einstein's Laws of Motion and Gravity
1. Newtonian gravity as as spacetime curvature
  - world line as time axis, change in velocity tilts time
  - therefore acceleration is curvature, bending time
  - gradient of acceleration is compound or intrinsic curvature
  - therefore div g = rho and curl g = 0 determine intrinsic curvature
2. Special relativity
  - synchronizing clocks
2. Prelude: Maxwell's equations and charge conservation


------------------------------------------------
Prehistory:
  Day, month, constellations, year

Ancient Greeks
  Eratosthenes: size of Earth, obliquity of ecliptic, star catalog
  Hipparchus: planetary position tables, precession of equinoxes, star catalog,
    lunar parallax (~60 Earth radii - he got 59), epicycles (with Apollonius)
  Ptolemy: Almagest, accurate epicycle model with sidereal periods of planets

Renaissance:
  Copernicus: Mostly inspirational and cultural, revived heliocentrism
  Brahe: Last and greatest naked eye astronomer, planetary position tables
  Kepler: Three laws
    - leveraged sidereal periodicity to work out points on orbits of Earth and
      Mars, first 3D planetary position measurements
    - guessed elliptical orbit shapes, fit to get 3D orbit models
    - exact times known at measured points have equal spacings (since derived
      by stepping earth and mars periods), find that these elliptical sectors
      have equal areas --> equal area law
    - from earth orbit model and first two laws, can quickly get ellipse
      parameters for the other planets
    - note cube-square law from derived orbits, which further reduces number of
      observations to derive an orbit

Telescope:
  Galileo: moons of Jupiter, phases of Venus, relativity
  Newton: laws of motion, universal gravitation
    - equal area law is conservation of angular momentum in central force field
    - inverse square law of accelearation is Kepler's first two laws
    - Kepler's third law follows from inverse square law
    - Jupiter's satellites obey Kepler's laws but different r**3/t**2 (Kepler)
    - Moon accelerates as inverse square of gravity at Earth's surface
    - r**3/t**2 is mass of gravitating object to conserve momentum


---------------------------------------------------------
Numerical Relationships

I. The Number Line
  A. Introduce origin and unit, coordinate is number
  B. Translation as changing origin --> addition
  C. Scaling as changing unit --> multiplication
  D. Distributive law (linearity)

II. The Number Plane
  A. Introduce origin and unit, now a point in plane and a square
     - coordinates are now a pair of numbers, left and up
  B. Translation - addition - just adds corresponding number in pairs
  C. Scaling - scalar multiplication - multiplies both numbers of pair
  D. Rotation - scaling changes size of unit, rotation changes orientation
     - scaling and rotation are both changes in unit square --> multiplication
  E. Distributive law still works for 2D multiplication and addition
  F. Ninety degree rotation and "imaginary" unit with square -1
  G. Using distributive law to work out coordinate multiplication rule
  H. Complex conjugate and Pythagorean theorem

III. Raising to powers
  A. Integer and rational powers
  B. As function of base --> power law
  C. As function of exponent --> exponential
  D. Exponent addition and multiplication (analog to distributive law?)
  E. Roots of unity and the unit circle
  F. Euler's construction

IV. Analytic Functions
  A. Linear mapping
  B. Scale and orientation varying from point to point
  C. Linear fractional mappings and projective plane
  D. Exponential function, geometrically
  E. Logarithmic function
  F. High school transcendental functions exp, log, trig, inverse trig
  G. angles and decibels

---------------------------------------------------------
Physical Geometry

0. Quantity and units
  A. Time - heartbeats, days, years
  B. Length - inches, hands, cubits, feet, strides
  C. Mass - density and volume "conjunctly", extensive versus intensive
  D. Charge - not directly sensible (requires instruments)
  E. Temperature - reducible to MLT, practical versus theoretical
  F?. Energy - reducible to MLT, unifies heat, work, potential

I. Number Line
  A. Units and Origin
  B. Translation as addition
  C. Scaling as multiplication
  D. Commutative and associative laws
  E. Distributive law and linearity
  F. Smooth mappings or functions

II. Number Plane
  A. Units and Origin
  B. Translation as addition
  C. Unit has both size and orientation, both fully specified by one edge
  D. Scaling and rotation as multiplication
  E. Negative one has a square root in the plane
  F. Commutative and associative laws
  G. Distributive law and linearity
  H. Smooth mappings or functions
  I. Relationship to number line, analytic continuation

III. Raising to powers
  A. Integer powers
  B. Add exponents to multiply, multiply exponents to raise to power
  C. Roots and rational powers, exponential functions
  D. Roots of unity and their powers
  E. Sine and cosine as exponential functions
  F. Analytic continuation of the exponential function
  G. Compound interest and Euler's formula for arbitrary powers of e
  H. Logarithmic functions - the other inverse of raising to powers
  I. All of high school math...

IV. Three dimensions and beyond
  A. Why there is no 3D, 4D, etc. number system
  B. Vectors, matrices, and linearity in 3D or higher
  C. Scaling and rotation as special kinds of matrix multiplication
  D. Symmetric matrices and eigenvectors
  E. Non-commutative multiplication
  F. Special case of 4D and what 3D inherits from it, quaternions

----------------------

Gravity causes spacetime curvature, mostly in the form of the gradient of an acceleration.  Gravity curves time, differently in different places.

Given that you know potential in some region and mass density just beyond its boundary, can you extend potential beyond boundary?  Bear in mind that you can begin near a single point with any value of gee as well as phi, since all you really need is the relative accelerations as you build a map of phi/gee.  This clearly doesn't work if you start in a region of zero density.  How about starting at a boundary and working inward?  Best idea seems to be to work outward, but each time you add mass you have to work backward over the whole region you've covered in order to make it consistent with the new source.  Point is, the equations for div gee and curl gee are never quite enough to work out even the relative accelerations as long as any mass remains outside region already considered.

