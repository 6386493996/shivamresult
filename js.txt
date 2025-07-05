// Simple search functionality (demo)
function searchSite() {
  var input = document.getElementById('searchInput').value.toLowerCase();
  if (input) {
    window.location.href = '/search.html?q=' + encodeURIComponent(input);
  }
}
