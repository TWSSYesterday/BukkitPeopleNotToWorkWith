Rolled his own hash algorithm, bragging how it was more secure than SHA, etc

```java
BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
		 
	      String line = null;
	      try {
	         line = br.readLine();
	      } catch (IOException ioe) {
	         System.out.println("IO error trying to read your phrase!");
	         System.exit(1);
	      }
	      
		char[] parts = line.toCharArray();
		String hash = "";
		for (char c : parts){
			int i = (int) c;
			//i = i/parts.length;
			hash = hash + i;
		}

		//Long h = Long.parseLong(hash);
		//h = h/parts.length;
		hash = hash + Character.toString(line.charAt(line.length() - 1)) + "";
//		if (passHash.equals(hash)){
//			System.out.println("Passwords do match.");
//		} else {
//			System.out.println("Passwords do not match.");
//		}
		passHash = hash; 
		System.out.println(hash);
```
