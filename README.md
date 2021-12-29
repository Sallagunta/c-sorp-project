# c-sorp-project
//second largest in array******************
        public void secondlargest(int []arr)
        {
            int  first=int.MinValue, second=int.MinValue;
            foreach(int i in arr)
            {
                if(i>first)
                {
                    second = first;
                    first = i;
                }
                else if(i>second)
                {
                    second = i;
                }
                
            }
            Console.WriteLine("second largest" + second);
  
            
        }
      //*****************************************************
