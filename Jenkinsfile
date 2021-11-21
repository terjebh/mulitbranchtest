node(any){
    try {
        stage('Checkout'){
            checkout scm
        }
   } catch(err) {
        echo "Handling errors".
   } finally {
       echo "Cleaning up"
   }
}
