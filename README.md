# kotlin-project1
fun main() {
    val output=probability(0.3F,0.6F,0.1F)
        }
fun probability(sunny:Float, cloudy:Float,notsunny:Float):Float{
    val value1:Float=sunny
    if (value1==sunny){
        println("the weather was sunny,the probability of Rose carrying an umbrella:")
        return sunny
    }
    else if(value1==cloudy){
        println("the weather was cloudy,the probability of Rose carrying an umbrella:")
        return cloudy
    }
    else{
        println("the weather was Not sunny,the probability of Rose carrying an umbrella:")
        return notsunny
    }


}
