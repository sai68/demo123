import psutil

def get_memory_info():
    memory = psutil.virtual_memory()
    total_memory = memory.total
    used_memory = memory.used
    free_memory = memory.free

    print(f"Total Memory: {total_memory / (1024 ** 3):.2f} GB")
    print(f"Used Memory: {used_memory / (1024 ** 3):.2f} GB")
    print(f"Free Memory: {free_memory / (1024 ** 3):.2f} GB")

if __name__ == "__main__":
    get_memory_info()
