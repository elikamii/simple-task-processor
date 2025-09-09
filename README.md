# simple-task-processor
def process_tasks(tasks):
    """
    Processes a list of tasks and prints a completion message for each.
    """
    print("Starting task processing...")
    for task in tasks:
        print(f"Task '{task}' has been completed.")
    print("All tasks finished successfully!")

if __name__ == "__main__":
    my_tasks = ["Download data", "Analyze data", "Generate report"]
    process_tasks(my_tasks)
