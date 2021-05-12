# Why Quantum Computing
## Quantum is future of computing.
Quantum computers are capable of solving exponential algorithmic problems
much faster than classical computers. With quantum computing the speed of
computation will reach new heights. As classical computers are achieving their
maximum possible speed with time, therefore quantum
computing is the only scope for further improvement.

# ALGORITHM / DESCRIPTION OF WORK
## Quantum Key Distribution ( Protocol )
Two pairs of states are used in this protocol, with each pair conjugating to the
other pair, and the two states orthogonal to each other within a pair. As a basis,
pairs of orthogonal states are named. The normal polarisation state pairs used
are either vertical (0°) or horizontal (90°) rectilinear bases, 45° and 135°
diagonal bases.

In this protocol, the first step is quantum transmission. Alice produces a random bit (0
or 1) and then chooses one of her two bases (in this case, rectilinear or
diagonal) randomly to pass it in. Depending on both the bit value and basis, as
shown in the adjacent table, she then prepares a photon polarisation state. For
example, a 0 is encoded as a vertical polarisation state in the rectilinear base
(+) and a 1 is encoded as a 135 ° state in the diagonal base (x). Alice then
transmits a single photon in the state described to Bob using the quantum
channel. This process is then replicated from the random bit level, with Alice
recording the status, basis and time of each photon sent.

According to quantum mechanics (particularly quantum indeterminacy), no
possible measurement distinguishes between the 4 different polarisation states
because they are not all orthogonal. The only measurement possible is between
any two orthogonal states (an orthonormal base). Thus, measuring on a
rectilinear basis for example, gives a horizontal or vertical result. If the photon
was produced as horizontal or vertical (as a rectilinear eigenstate), then thecorrect state is measured, but the rectilinear measurement returns randomly as
horizontal or vertical instead if it was produced as 45 ° or 135 ° (diagonal
eigenstates). Furthermore, after this measurement, the photon is polarised in
the state in which it was measured (horizontal or vertical), with all information
regarding its initial polarisation lost.

Since Bob does not understand the basis on which the photons were encoded,
all he can do is select either rectilinear or diagonal, a random basis for
calculation. He does this with each photon he receives, recording the time, the
basis of the measurement used and the measurement effect. After Bob has
counted all the photons, he communicates with Alice over the public classical
channel. Alice broadcasts the basis on which each photon has been sent and the
basis on which Bob has measured each photon. They both discard photon
measurements (bits) where Bob has used a different basis, which is half on
average, leaving half the bits as a shared key.

# Scope in Future
This protocol can be very effective for future reference,we can also use such
protocol in IoT devices to avoid Distributed Denial of Service Attack(DDOS)
such as Mirai, We can also provide strong security to online International
Money transfer.
