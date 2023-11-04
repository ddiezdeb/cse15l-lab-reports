
Below is an example of the Junit test I ran that included failure inducing input. I was expecting a reversed list, but instead I got back a palindrome that replaced the first half of the list with the second half.

`@Test
  	public void testReverseInPlaceThreeInputs() {
    int[] input1 = { 1,2,3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3,2,1 }, input1);
	}` 

 
Next is an example of a test that passed the faulty code.
      '@Test
  	public void testReverseInPlaceSingleInput() {
    int[] input1 = { 1};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 1}, input1);
	}' 
