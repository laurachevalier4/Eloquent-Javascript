# Eloquent-Javascript
Practice question solutions for the online textbook, "Eloquent Javascript"
function countBs(string) {
  var count = 0;
  for (var i = 0; i < string.length; i++) {
    if (string.charAt(i) == "B")
      count += 1;
  }
  return count;
}

function countChart(string, character) {
  var count = 0;
  for (var i = 0; i < string.length; i++) {
    if (string.charAt(i) == character)
      count += 1;
  }
  return count;
}
  

console.log(countBs("BBC"));
// → 2
console.log(countChar("kakkerlak", "k"));
// → 4
