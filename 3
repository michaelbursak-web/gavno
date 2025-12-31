const data = [
  {
    id: 531,
    name: "Leonid Kevilov",
    nationality: "🇷🇺 Russia",
    details: "BASE fatality record"
  },
  {
    id: 530,
    name: "John Doe",
    nationality: "🇺🇸 USA",
    details: "Sample record"
  },
  {
    id: 529,
    name: "Max Mustermann",
    nationality: "🇩🇪 Germany",
    details: "Sample record"
  }
];

const tbody = document.querySelector("tbody");

function render(list) {
  tbody.innerHTML = "";
  list.forEach((item, i) => {
    const tr = document.createElement("tr");
    tr.id = `bfl${item.id}`;
    tr.innerHTML = `
      <td>${i + 1}</td>
      <td>${item.name}</td>
      <td>${item.nationality}</td>
      <td>${item.details}</td>
    `;
    tbody.appendChild(tr);
  });
}

render(data);

function sortTable(col) {
  data.sort((a, b) =>
    Object.values(a)[col] > Object.values(b)[col] ? 1 : -1
  );
  render(data);
}

document.getElementById("search").addEventListener("input", e => {
  const v = e.target.value.toLowerCase();
  render(data.filter(d => d.name.toLowerCase().includes(v)));
});

function toggleDark() {
  document.body.classList.toggle("dark");
}

// Auto-scroll if hash exists
if (location.hash) {
  setTimeout(() => {
    document.querySelector(location.hash)?.scrollIntoView();
  }, 300);
}
