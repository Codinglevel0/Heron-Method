# Heron-Method
A task I was given in class, but I don't know where to even start!
This is what we were given:

The Heron method is a method for computing square roots that was known to the ancient Greeks. If x is a guess for the value sqrt(a), then the average of x and a/x is a better guess.
Implement a class RootApproximator that starts with an initial guess of 1 and whose nextGuess method produces a sequence of increasingly better guesses. Supply a method hasMoreGuesses that returns false if two successive guesses are sufficiently close to each other (that is, they differ by no more than a small value like 1E-9).

I want you to use this code in your main class:

RootApproximator approx = new RootApproximator(numToGuess);
while (approx.hasMoreGuesses())
	System.out.println(approx.nextGuess());

And the RootApproximator class should include:

public class RootApproximator
{
	private final double GUESS_WITHIN = 1E-9;
	// and other instance variables!!

	public RootApproximator(int numberToSquareRoot)
	{
		...
	}
	public boolean hasMoreGuesses()
	{
		...
	}
	public double nextGuess()
	{
		...
	}
}

