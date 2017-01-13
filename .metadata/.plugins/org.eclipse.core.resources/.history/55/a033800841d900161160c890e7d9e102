package arrCalcEngine;

public class calcengine {

	public static void main(String[] args) {
		double[] rightVals = {100.0d, 25.0d, 225.0d, 11.0d};
		double[] leftVals = {20.0d, 50.d, 3.0d, 10.0d};
		char[] opCodes = {'d', 'a', 's', 'm'};
		double[] results = new double[opCodes.length];
		
		for(int i = 0; i < opCodes.length; i++){
	      switch(opCodes[i]) {
	    	  case 'a':
	            results[i] = leftVals[i] + rightVals[i];
	            break;
	      	  case 's':
	            results[i] = leftVals[i] - rightVals[i];
	            break;
	      	  case 'd':
	            results[i] = leftVals[i] / rightVals[i];
	            break;
	      	  case 'm':
	            results[i] = leftVals[i] * rightVals[i];
	            break;
	      }
		}
		
		for(double theResult : results){
			System.out.print("result = ");
			System.out.println(theResult);
		}
	}

}
