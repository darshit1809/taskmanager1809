const tasks = [];
const addTask = (title, status, priority) => {
    tasks.push({ title, status, priority });
};
const filterByStatus = (status) => tasks.filter(task => task.status === status);
const findHighPriorityTask = () => tasks.find(task => task.priority === 5);
const getTaskSummaries = () => tasks.map(task => `Task: ${task.title}, Status: ${task.status}`);
const logAllTasks = () => {
    tasks.forEach(task => {
        console.log(`Title: ${task.title}, Status: ${task.status}, Priority: ${task.priority}`);
    });  };

addTask("Buy medicine", "Pending", 3);
addTask("Complete project", "Completed", 5);
addTask("Complete assignments", "Pending", 4);

console.log("Filtered Tasks (Pending):", filterByStatus("Pending"));
console.log("High Priority Task:", findHighPriorityTask());
console.log("Task Summaries:", getTaskSummaries());
logAllTasks();
