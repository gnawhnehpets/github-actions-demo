{
  properties: {
    path: { type: 'keyword' },
    tenantId: { type: 'keyword' },
    productName: { type: 'keyword' },
    tenant: { type: 'keyword' },
    tenantTags: { type: 'keyword' },
    tags: { type: 'text' },
    doc: { type: 'text' },
    plainDoc: { type: 'text' },
    title: { type: 'text', fielddata: true, store: true },
    titleKW: { type: 'keyword', normalizer: 'case_insensitive_normalizer' },
    description: { type: 'text' },
    type: { type: 'text' },
    lastModified: { type: 'date', format: 'epoch_millis' },
    comboKey: { type: 'text' },
    branchName: { type: 'text' },
    esRegion: { type: 'keyword' }
  }
}