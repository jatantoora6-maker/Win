("/mnt/data/Primeland_Properties_Website.zip") work = Path("/mnt/data/primeland_pro") if work.exists(): shutil.rmtree(work) work.mkdir(parents=True)
work / "primeland_website"
