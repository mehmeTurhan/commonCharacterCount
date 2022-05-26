int solution(String s1, String s2) {
    int numMatch=0;
    for(int i=0;i<s1.length();i++){
        if(s2.contains(String.valueOf(s1.charAt(i)))){
            numMatch++;
            s2=s2.replaceFirst(String.valueOf(s1.charAt(i)), "");
        }
    }
    return numMatch;
}
